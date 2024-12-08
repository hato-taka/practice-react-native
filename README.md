# React Native の説明

React Native では、ウェブ開発で使用される HTML タグの代わりに、特定のコンポーネントを使用します。以下に、React Native の主要なタグ（コンポーネント）を紹介します。

## 基本的なコンポーネント

### View
`View` は React Native の最も基本的なコンポーネントで、レイアウトやスタイリングのためのコンテナとして使用されます。HTML の `<div>` タグに相当します[3][4]。

### Text
`Text` コンポーネントはテキストを表示するために使用されます。すべてのテキスト要素は `Text` コンポーネント内に配置する必要があります[1][3][4]。

### Image
画像を表示するためのコンポーネントです。

### TextInput
ユーザーからのテキスト入力を受け付けるためのコンポーネントです。

### ScrollView
スクロール可能なコンテンツを作成するためのコンポーネントです。

## リスト関連コンポーネント

### FlatList
効率的にスクロール可能な長いリストを表示するためのコンポーネントです[1]。

### SectionList
セクション付きのリストを表示するためのコンポーネントです[1]。

## その他のコンポーネント

### Button
タッチ可能なボタンを作成するためのコンポーネントです[2]。

### TouchableOpacity
タッチ操作に反応する要素を作成するためのコンポーネントです[1][2]。

### StatusBar
デバイスのステータスバーを制御するためのコンポーネントです[3]。

これらのコンポーネントを組み合わせることで、React Native アプリケーションのユーザーインターフェースを構築します。各コンポーネントは特定の目的を持ち、適切に使用することでネイティブな外観と操作性を実現できます。

React Native では、これらのコンポーネントを JSX 構文を使って記述します。例えば：

```jsx
<View style={styles.container}>
  <Text>Hello, React Native!</Text>
  <Button title="Press me" onPress={() => alert('Button pressed')} />
</View>
```

このように、HTML タグの代わりに React Native のコンポーネントを使用してアプリケーションの UI を構築します[3][4]。

Citations:
[1] https://note.com/npaka/n/n72a829aa6cbb
[2] https://rocksystem.co.jp/blog/page.php?entry_id=103
[3] https://zenn.dev/yutama_kotaro/articles/7a0d1d771d2ca3
[4] https://qiita.com/macotok/items/591705b768db0473e1d3


---

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
