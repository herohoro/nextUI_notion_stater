# Based on Next UI & Next.js Notion Starter kit
- 簡単に見た目のいいサービスを作るため、[Next UIライブラリ](https://nextui.org/)を使用。
- 複雑なページネーションは[Next.js Notion Starter kit](https://github.com/transitive-bullshit/nextjs-notion-starter-kit)にお任せ。
- Notionで普段使用するブロックの種類はNotion公式APIより充実したサポートのある[react-notion-x](https://github.com/NotionX/react-notion-x)を使用。
  
# Set up
1. Next.js Notion Starter kitの[Setup](https://github.com/transitive-bullshit/nextjs-notion-starter-kit#setup)をする
2. Next.js Notion Starter kit ディレクトリ内に[Next UIライブラリをインストール](https://nextui.org/docs/guide/getting-started#installation)する
3. rootにあたるpages/index.jsに[NextUIProviderをappで使えるよう記述](https://nextui.org/docs/guide/getting-started#setup)する
4. pages/__app.tsxにも[NextUIProviderをデフォルトで使えるよう記述](https://nextui.org/docs/guide/getting-started#next.js)
5. Server Renderをpages/__document.tsxで[調整](https://nextui.org/docs/guide/nextui-plus-nextjs#server-render)する
  
# Using
Next UI で装飾をしたい箇所に[記述](https://nextui.org/docs/guide/getting-started#using-nextui-components)する。  
※　例では[ボタン](https://nextui.org/docs/components/button)ですが他の装飾に関してはNEXT UI公式ドキュメント参照