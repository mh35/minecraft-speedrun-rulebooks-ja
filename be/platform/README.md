# プラットフォームの規則

**注釈: 以下の規則については、個別カテゴリの規則により上書きされることがある**

**疑問がある場合、[FAQ](https://www.speedrun.com/mcbe/thread/vdv9t)に答えがあるかもしれない**

[戻る](../README.md)

## 一般規則

* いかに明言がない限り、エミュレータは禁止される

## PC

* タッチスクリーンを除き、いかなる入力手段も許可される

### Windows

* Windows 10/11版でプレイしなければならない
* 複数のMinecraft Bedrockのインスタンスを起動するには、Windowsのレジストリの操作によってのみ許可される
    * 以下のPowerShellスクリプトの実行により可能である

```pwsh
$packageFullName = (Get-AppxPackage -Name Microsoft.MinecraftUWP).PackageFullName
if ([String]::IsNullOrEmpty($packageFullName)) {
    Write-Host "Could not get 'Microsoft.MinecraftUWP' package." -ForegroundColor Red
    return
}
$registryPath = "HKCU:SOFTWARE\Classes\Extensions\ContractId\Windows.Launch\PackageId\$packageFullName\ActivatableClassId\App\CustomProperties"
if (!(Test-Path -Path $registryPath)) {
    New-Item -Path $registryPath -ItemType RegistryKey -Force | Out-Null
}
Set-ItemProperty -Path $registryPath -Name "SupportsMultipleInstances" -Value 1 -Type DWORD
```

* 同じワールドに複数のインスタンスから参加することは許可されない
* 走行中のまれなファイル保存のグリッチは拒否されることがある(例えばシード値やチャンクの複製や、その他のグリッチが該当する)

### Linux / MacOS

* LinuxおよびmacOSのユーザはPocket Editionをプレイしなければならず、[Minecraft Bedrock Launcher](https://mcpelauncher.readthedocs.io/en/latest/getting_started/index.html)を経由してプレイしたならばPC版の順位表に提出しなければならない

## モバイル

* 以下のプラットフォームのいずれかでプレイしなければならない
    - Android
    - iOS
    - Windows Phone
* いかなる入力手段も許可される

## ゲーム機

* 以下のプラットフォームのいずれかでプレイしなければならない
	- PS4
	- PS5
	- Xbox One
	- Xbox Series X
	- Xbox Series S
	- Nintendo Switch
	- Nintendo Switch 2
	- fireTV
* タッチスクリーンを除き、いかなる入力手段も許可される

## 仮想現実

* 仮想現実(VR)による走行は、実際の物理的な端末に従う。すなわち、PCによりヘッドセットに配信されたものをプレイしたならばPC版、ゲーム機により動作するならばゲーム機の順位表に提出しなければならないということである
