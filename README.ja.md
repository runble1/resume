# kawamataryo の職務経歴書

![textlint](https://img.shields.io/github/workflow/status/runble1/resume/lint%20text?label=textlint&logo=github&color=yellow)
![build pdf](https://img.shields.io/github/workflow/status/runble1/resume/build-pdf?label=build%20pdf&logo=github)
![create issue](https://img.shields.io/github/workflow/status/runble1/resume/create%20issue?label=create%20issue&logo=github&color=orange)
![release date](https://img.shields.io/github/release-date/runble1/resume?color=blue&logo=github)

[ [English](https://github.com/runble1/resume) | 日本語 ]

## Data

- [GitHub Pages](https://runble1.github.io/resume/)
- [PDF](https://github.com/runble1/resume/releases)
- [File](https://github.com/runble1/resume/blob/master/docs/README.md)

## Features

### 💅 Lint text

[textlint](https://github.com/textlint/textlint) での自動校正が可能です。

```
$ yarn lint --fix
```

[husky](https://github.com/typicode/husky) によって commit 前にも自動で実行されます。  
校正のルールは`.textlintrc`に記載しています。

### 📝 Convert Markdown to PDF

[md-to-pdf](https://www.npmjs.com/package/md-to-pdf) での PDF 生成が可能です。

```
$ yarn build:pdf
```

出力される PDF は CSS で任意のスタイルを設定可能です。`pdf-configs/style.css`を編集してください。

### 🛠 Create release

`v**` tag をつけて push すると GitHub Actions でビルドが走り、PDF の生成、Release の作成、Assets へ PDF の登録が実行されます。

```
$ git commit -m "add job"
$ git tag v1.0
$ git push origin --tags
```

### 📆 Remind update

GitHub Actions の schedule trigger で 3 ヶ月に 1 回、職務経歴書の内容更新を促す issue が自動生成されます。

期間の変更、Job の停止は[.github/workflows/create-issue.yml](https://github.com/kawamataryo/resume/blob/master/.github/workflows/create-issue.yml) を編集してください。
