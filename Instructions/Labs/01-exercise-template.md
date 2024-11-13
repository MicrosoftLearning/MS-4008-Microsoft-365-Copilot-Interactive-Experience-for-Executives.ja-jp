---
lab:
  title: 演習のタイトル
  module: Learn module title
---
<!--
Edit the metadata above to manage the list of exercises in the home page of the GitHub site that gets generated.
You can delete the module and edit index.md in the root of the repo to customize the display so that only the exercises are listed
To enable GitHub page publishing, edit the Page settings for the repo and publish from the main branch
-->

# 演習のタイトル <!-- match title in metadata above (and Learn Exercise unit and ILT slide)-->

この演習では、次のことを行います。 <!-- provide a description of what they'll do and why it;s important -->

この演習の所要時間は約 **XX** 分の見込みです。 <!-- update with estimated duration -->

## 開始する前に

<!--
Add steps to get the learner to the starting point" for the exercise.
This might be cloning the repo and running a script or performing some manual steps.
Only include this section if its necessary to do some pre-exercise setup AND the same setup steps are required for self-paced (on Learn) and managed (in hosted ILT lab profiles) scenarios. Otherwise delete this section.
If self-paced /ILT-specific setup steps are required, include them in the Learn "Exercise" unit from where they open this exercise and in the Skillable lab profile instructions before this markdown file is imported.
 -->

この演習を開始する前に、以下を行う必要があります。

1. 手順 1
1. ステップ 2
1. その他。

## タスク <!-- Change to an appropriate task title with an imperative verb phrase (e.g. "Do something") -->

まず、次を行う必要があります。

1. 手順 1
1. この手順には例に `inline code formatting` が含まれています。これは、ホストされた Skillable 環境に [T] リンクが作成されるため、学習者が何か (コードだけでなく何でも) 入力する必要がある場合に使用されます。
1. 学習者に Web サイトを開いてもらう必要がある場合は、リンク (HTML GitHub ページをクリックして開くことができるようにするため) と、コードとして書式設定された URL (ホストされた VM ブラウザーで入力できるようにするため) の両方を含めます。 たとえば、"[Bing](https://www.bing.com) Web サイト (`https://www.bing.com`) を開きます" などです。
1. 学習者にファイル (またはファイルの集まりの zip 形式) をダウンロードしてもらう必要がある場合は、このリポジトリの Allfiles フォルダーにファイルを格納し、URL を**そのまま** ("`https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json` から[ファイル名](https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json)をダウンロードします" のように) 使用します。
1. または、対象者が開発者で、その方が適切だと思われる場合は、このリポジトリをクローンさせることができます。
1. 複数行のコード ブロックを入れる必要がある場合は、箇条書きのインデントに合わせてインデントします。

    ```python
    # This is an example of an
    # indented code block.
    ```

1. スクリーンショットを入れる必要がある場合は、適切なサイズに変更します (そのため、部分的なスクリーンショットでの "標準" で書式設定されたテキストは、このテキストとほぼ同じサイズです。ほとんどの場合は、アプリケーション ウィンドウ全体のスクリーンショットを 800 x 600 ピクセル (およそ) にするようにしてください)。 画像は **Media** サブフォルダーに格納し、Markdown を使用してページに追加します (ファイル名とフォルダー名では大文字と小文字が区別されることを覚えておいてください)。 画像がリスト内にある場合は、次のようにインデントします。

    ![アプリケーションのスクリーンショット。](./Media/edge-copilot.png) 

1. そのように行う理由を説明する必要がある場合、または情報への追加のコンテキストやリンクを提供する必要がある場合は、次のように注記を使用します。

    > **注**: これは注記です。

1. マイペースで進められるラボ環境とホストされたラボ環境で異なる可能性のある手順を示す場合は、柔軟に対応してください。 次に例を示します。
    - "Azure 資格情報を使用してサインインします" (Learn 演習ページで個人用サブスクリプションを使用するか試用版を作成するための Learn 固有の手順があり、Skillable ラボ プロファイルで指定された Cloudslice 資格情報を使用するための ILT 固有の手順があると仮定)
    - "既存のリソース グループを選択するか、新しいリソース グループを作成します" (Skillable CS-R Cloudslice が使用されている場合に、使用するリソース グループを学習者に伝える注記をラボ プロファイルに入れたと仮定)
    <!-- The key point is that this markdown file should be environment-agnostic - you need to provide explicit details of things that can vary OUTSIDE of this file (in the Learn exercise page or the Skillable lab profile instructions) -->
1. その他。

## 次の作業

これから行うのは以下です。

1. 手順 1
1. ステップ 2
1. その他。

## サブタスクを含むタスク

時には、タスクをより小さなチャンクに分割したい場合があります。

### サブタスク 1

1. 手順 1
1. ステップ 2
1. など

### サブタスク 2

1. 手順 1
1. ステップ 2
1. その他。

## クリーンアップ

<!-- Good practice - especially as self-paced learners will be using their own subscriptions -->
<!-- Delete this section if it is not needed -->

演習が完了したので、不要なリソースの使用を避けるために、作成したクラウド リソースを削除する必要があります。

1. 手順 1
2. その他。
