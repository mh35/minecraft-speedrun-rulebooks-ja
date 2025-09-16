# 共通規則

**注釈: 以下の規則については、個別カテゴリの規則により上書きされることがある**

## 一般的規則

* ゲームを改変する外部ツールの使用は、いかなる方法や形をもってしても禁止される。
* 今のところ、1.2.6系統のモバイル版で発生する複製グリッチは、特に明言されていない限り、あらゆるカテゴリにおいて禁止されている
* 走行中、ゲーム内のコマンドを実行してはならない
    - これはバグあり走行であっても例外ではない。走者は多くの場合、コマンドのグリッチを利用しようとする。コマンドのグリッチはこのルールに抵触し禁止される。
* あらゆるワールド設定の変更は、ワールド作成後厳格に禁止される
    - これにはゲームモードの変更も含む
    - ワールドの難易度変更は、それがピースフルへ、もしくはピースフルからの変更でない限り認められる
        + 難易度が変更された走行を提出する際には、提出フォームにある「World Difficulty」の項目にはプレイ中の最低難易度を指定すること
        + 例えば、プレイ中にハードからノーマルに変更した際は、ノーマルの難易度として扱われる
* ワールドの再読み込み(ワールドを閉じたうえで再び開く行為)は、走行をバグありのものとみなす。
    - ただし、この再読み込みが走行に影響を及ぼさなかったと証明できる場合、これ単体でバグありとみなさずバグなしのものとして維持することができる。
    - これには以下のものを含むがそれに限らない
        + ネザーの屋根の上でスタックしてしまった
        + エンティティがおおむねY=32000近辺にある
        + ワールドの再読み込みなく現実的な修復が不可能なバグ全般
* 走者の創意工夫や独創性を推進するが、ルールに対して不適切な試みを行わないこと。利用されることを意図していないルールの抜け穴の不正使用は、走行の認定拒否の原因となる
    - 抜け穴を見つけた際は、代わりにモデレータに通報することを推奨する。

## 提出に関する規則

* 走者は希望する任意のバージョンで記録の提出が可能である。
    - 特定の個別レベルカテゴリについては、特定のバージョンもしくはバージョンの範囲を要求される場合がある
    - ベータ版で行われるすべての走行はカテゴリ拡張にあるベータ版のカテゴリに提出されなければならない
    - 明言されていない限り、ベータ版の走行の提出は認められない
* 走行の長さより顕著に長い動画を提出する場合、提出の説明に走行の開始と終了のタイムスタンプを指定すること
    - これは必須ではないが、モデレータの検証にかかる時間の短縮のため強く推奨される
    - 十分待ち行列が長い場合、タイムスタンプを指定しての再提出の指示を含むメッセージの上、提出を拒絶することがある
* トップランナーは走行に関する追加の証拠の提出に備えなければならない。これには以下を含む。
    - セッションの完全な無加工の録画
    - 過去の試行の録画
    - 走行に用いたワールドのフォルダ(ただしPC版に限る)
    - ワールドのシード値(ランダムシードの場合) - すべての提出についてシード値の提出が推奨されるが、必須ではない
* 他の走者についても、これらの追加の証拠の提出に必要に応じて応じられるよう備えるべきである(が、多くの場合必須ではない)。

## ゲームの修正に関する規則

* あらゆる種類のテクスチャパックは禁止である
* 走者は、options.txtにあるゲームの設定を変更してよい
    - これはあらゆる視覚設定の変更(例えば遅延軽減のために垂直同期を変更)を許可する
    - 走者の利益のためになりうるあらゆる変更(例: ガンマ値)は許可されない
* 他のいかなるゲームの修正およびビヘイビアパックは禁止である
* いかなる形であっても、ゲーム外の補助(マクロ・スクリプトなど)は禁止である
    - ワールドリセットのマクロは許可される
    - モバイル版においては、以下の所定のキーバインドを行う限りにおいて、キーマッパーが許可される
        * Qはアイテムを捨てる
        * F5は視点変更
        * Shiftはしゃがむ

## 証拠に関する規則

* 順位表に掲載されるためには、証拠が必要である
    - 順位表に提出するにあたり、リタイムおよびアーカイブの目的のためにモデレータチームに走行のダウンロードの許可を与えるものとする
* 証拠は閲覧可能な形の動画でなければならない
    - 協力走行の場合、ホストプレイヤーのみ証拠の提出が必須である
    - あらゆる動画ホスティングサービスを用いることができ、動画は一般公開されている必要はない。ただし、YouTubeの公開動画を提出することが強く推奨される
        + 動画が一般公開でない場合、限定公開であるか、別の形でモデレータに共有されなければならない。
    - 最低の品質指定はないものの、最低でも480p・30fpsを推奨する
    - 大量のドロップフレームがあり、正確なリタイムが困難な場合、走行が拒絶されることがある
    - 音声は必須ではない
    - 以下のWebサイトは動画の提出に用いることが禁止であるため、用いてはならない
        + twitch.tv
        + discord.com
        + NSFW(性的なコンテンツなどを主題とし、業務中の閲覧に適しない)のコンテンツを主題とするあらゆるWebサイト
* タイマーは必須ではない
* いかなる形であっても、走行の時間に影響する動画の編集は厳禁である
    - 動画の切り抜きや速度変更は、この禁則に該当する
    - 一方、動画にBGMを付けたり、動画の冒頭にオープニングを追加するなどは問題ない
        + BGMには好きな音楽を用いてよい
* すべての動画はワールド生成の過程および走者が新規に作成されたワールドに入る部分が含まれていなければならない
* ゲームを一時停止してもよいが、それはあらゆる入力の前に行わなければならない
* 検証時にゲーム全体のカテゴリについては**トップ5**、個別レベルカテゴリについては**世界記録**の走行を終えた場合、ワールドから出たうえでメインメニューに戻らなければならない
* Windowsにおいては、検証時にゲーム全体のカテゴリについては**トップ5**、個別レベルカテゴリについては**世界記録**の走行を終えた場合、新しいPowerShellのウィンドウにおいて走行の開始・終了時に以下のコマンドを実行しなければならない。

```pwsh
param (
	[Parameter(Mandatory=$false)] [string] $installationDir,
	[Parameter(Mandatory=$false)] [string] $outputFile,
	[Parameter(Mandatory=$false)] [bool] $Check = $false
)
$outputFile = if ([string]::IsNullOrEmpty($outputFile)) {
	[string] $currentTime = Get-Date -Format "yyyy-MM-dd_HH-mm-ss"
	[string] $desktopFolder = [Environment]::GetFolderPath([Environment+SpecialFolder]::Desktop);
	[string] $outFolderName = "mcbe-speedrunning";
	[string] $outFolder = Join-Path `
		-Path $desktopFolder `
		-ChildPath $outFolderName
	if (-not (Test-Path $outFolder)) {
		New-Item -Path $desktopFolder -Name $outFolderName -ItemType "directory" | Out-Null
	}
	Join-Path -Path $outFolder -ChildPath "Hashes_$currentTime.txt"
} else {
	$outputFile
}

if ([string]::IsNullOrEmpty($outputFile)) {
	throw [System.IO.FileNotFoundException] "Couldn't find the output file. Please report this issue"
}

if ($Check) {
	[string[]] $hashStrings = Get-Content -Path "$outputFile"
	[string] $mainHash = $hashStrings -join ''
	$(Get-FileHash -InputStream ([IO.MemoryStream]::new([char[]]$mainHash))).Hash
} else {
	[Microsoft.Windows.Appx.PackageManager.Commands.AppxPackage] $mcbeAppx = Get-AppxPackage -Name Microsoft.MinecraftUWP
	$installationDir = if ([string]::IsNullOrEmpty($installationDir)) {
		$mcbeAppx.InstallLocation
	} else {
		$installationDir
	}

	if ([string]::IsNullOrEmpty($installationDir)) {
		throw [System.IO.FileNotFoundException] "Couldn't find the minecraft installation. Please report this issue"
	}

	[string] $mcbeStateFolder = Join-Path -Path $env:LOCALAPPDATA -ChildPath "Packages\$($mcbeAppx.Name)_$($mcbeAppx.PublisherId)\LocalState\games\com.mojang"
	[string] $globalResourcePacksFile = $(Join-Path -Path $mcbeStateFolder -ChildPath "minecraftpe\global_resource_packs.json")
	if ([System.IO.File]::Exists($globalResourcePacksFile)) {
		[PSCustomObject] $globalResourcePacks = Get-Content -Path $globalResourcePacksFile | ConvertFrom-Json
		echo "Activated global resource packs are 0? $($globalResourcePacks.Count -eq 0)"
	} else {
		echo "No global resources file found"
	}
	[System.IO.DirectoryInfo] $lastWorld = Get-ChildItem $(Join-Path -Path $mcbeStateFolder -ChildPath "minecraftWorlds") -Directory | Sort-Object LastWriteTime -Descending | Select-Object -First 1
	if ($lastWorld) {
		[string] $worldResourcePacksFile = $(Join-Path -Path $lastWorld.FullName -ChildPath "world_resource_packs.json")
		if ([System.IO.File]::Exists($worldResourcePacksFile)) {
			[PSCustomObject] $worldResourcePacks = Get-Content -Path $worldResourcePacksFile | ConvertFrom-Json
			echo "Activated latest world resource packs are 0? $($worldResourcePacks.Count -eq 0)"
		} else {
			echo "No world resource pack file found"
		}
		[string] $worldBehaviorPacksFile = $(Join-Path -Path $lastWorld.FullName -ChildPath "world_behavior_packs.json")
		if ([System.IO.File]::Exists($worldBehaviorPacksFile)) {
			[PSCustomObject] $worldBehaviorPacks = Get-Content -Path $worldBehaviorPacksFile | ConvertFrom-Json
			echo "Activated latest world behaviour packs are 0? $($worldBehaviorPacks.Count -eq 0)"
		} else {
			echo "No world behaviour pack file found"
		}
	} else {
		echo "No last world found"
	}

	[int] $totalFiles = (Get-ChildItem -Path $installationDir -Recurse -File).Count
	[int] $progress = 0
	[int] $updateInterval = [Math]::Ceiling($totalFiles / 100)

	[string[]] $hashStrings = Get-ChildItem -Path $installationDir -Recurse -File | ForEach-Object {
		$hash = Get-FileHash -Path "$($_.FullName)"
		"$($_.Name)=$($hash.Hash)"

		if (++$progress % $updateInterval -eq 0) {
			$percentComplete = [Math]::Floor(($progress / $totalFiles) * 100)
			Write-Progress -Activity "Calculating Hashes" -Status "Progress: $percentComplete%" -PercentComplete $percentComplete
		}
	}
	$hashStrings | Out-File -FilePath $outputFile
	[string] $mainHash = $hashStrings -join ''
	$(Get-FileHash -InputStream ([IO.MemoryStream]::new([char[]]$mainHash))).Hash
}
```

上記のスクリプトはランダムシードの場合は開始・終了時に実行しなければならず、セットシードであっても実行することが強く推奨される。

PowerShellのウィンドウを開くには、Windows+Rを押した後、「powershell」と入力したのちEnterキーを押す。上記のスクリプトを貼り付けた後、出力の終了を確認したうえで、終了後に再び実行する前にウィンドウを閉じること。

PowerShellのユーザー名を隠したい場合、`notepad $PROFILE`と入力したうえで、以下の行を追加するとよい。

```pwsh
function prompt {"PS: >"}
```

## 計時に関する規則

### 計時は以下のタイミングで始まる

* 視点変更・チャットを開く・エモート・一時停止メニューを開く以外のあらゆる操作
* あらゆるプレイヤーの動き、もしくはノックバックを伴うダメージ
* 協力走行においては、少なくとも1名のプレイヤーが上記2つのアクションを行ったとき

### 注釈・例外

* ブロックの中にスポーンし、それにより押し出された場合、計時は開始しない
* 何の効果もない入力(例えば何もないところの右クリックなど)は、計時は開始しない
* ワールド読み込み完了時から、走行開始まで合理的な範囲であれば待ってもよい
    - 合理的な時間を超えているならば、ワールド読み込み完了時をもって計時を開始する
    - 合理的な時間については、審査員の裁量に依存する
* ゲーム全体のカテゴリについては10ミリ秒単位とする。同順位の場合、ミリ秒単位とする
* 個別レベルカテゴリについてはミリ秒単位とする

## ワールド作成に関する規則

**注釈: すべての動画はワールド作成の設定を表示しなければならない**

* ゲームモード: サバイバル
* 難易度: イージー・ノーマル・ハード
    - ピースフルはピースフルを指定したカテゴリで許可される
* 開始時に地図を所持: オフ
* ボーナスチェスト: オフ
* デフォルトのプレイヤー権限: メンバー
* ワールドタイプ: 無限
* 味方へのダメージ: オン
* 火の延焼: オン
* TNT火薬の爆発: オン
* モブのアイテムドロップ: オン
* タイルからのドロップ: オン
* 夜を寝てスキップ: オン
* 必要な睡眠中のプレイヤー: デフォルト
* 即時リスポーン: オフ
* リスポーンブロックが爆発する: オン
* リスポーン範囲: デフォルト
* 実験的機能: オフ
* チート: オフ
