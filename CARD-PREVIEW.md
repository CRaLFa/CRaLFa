# カード比較プレビュー

OS / ブラウザをダークモードに切り替えて、それぞれの見え方を比べる。
確認が終わったらこのファイルは削除する。

## A. 現状: gh-card.dev (ダーク非対応)

<a href="https://github.com/CRaLFa/dotfiles"><img src="https://gh-card.dev/repos/CRaLFa/dotfiles.svg" width=420></a>
<a href="https://github.com/CRaLFa/md-parser"><img src="https://gh-card.dev/repos/CRaLFa/md-parser.svg" width=420></a>

## B. github-readme-stats の pin カード (picture で切り替え)

<a href="https://github.com/CRaLFa/dotfiles"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api/pin/?username=CRaLFa&repo=dotfiles&theme=github_dark" /><img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=CRaLFa&repo=dotfiles" width=420 /></picture></a>
<a href="https://github.com/CRaLFa/md-parser"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api/pin/?username=CRaLFa&repo=md-parser&theme=github_dark" /><img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=CRaLFa&repo=md-parser" width=420 /></picture></a>

## C. GitHub Socialify (theme=Auto、URL 1 本)

<a href="https://github.com/CRaLFa/dotfiles"><img src="https://socialify.git.ci/CRaLFa/dotfiles/svg?theme=Auto&description=1&language=1&stargazers=1&forks=1&pattern=Plus" width=420></a>
<a href="https://github.com/CRaLFa/md-parser"><img src="https://socialify.git.ci/CRaLFa/md-parser/svg?theme=Auto&description=1&language=1&stargazers=1&forks=1&pattern=Plus" width=420></a>

## D. Socialify を装飾なしで詰めた版

<a href="https://github.com/CRaLFa/dotfiles"><img src="https://socialify.git.ci/CRaLFa/dotfiles/svg?theme=Auto&description=1&language=1&stargazers=1&pattern=Solid&font=Inter" width=420></a>
<a href="https://github.com/CRaLFa/md-parser"><img src="https://socialify.git.ci/CRaLFa/md-parser/svg?theme=Auto&description=1&language=1&stargazers=1&pattern=Solid&font=Inter" width=420></a>

---

寸法の目安 (width=420 で表示したときの高さ):

| | 元サイズ | 420px 幅での高さ |
| - | - | - |
| gh-card | 442x109 | 約 104px |
| pin カード | 442x109 相当 | 約 104px |
| Socialify | 1280x640 | 約 210px |

Socialify はカード 1 枚が約 2 倍の高さになる。
現在リポジトリカードは 20 枚あるため、全部置き換えるとページはかなり縦に伸びる。
