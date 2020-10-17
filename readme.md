<div align="center">
	<h1>🚀 C# Runner</h1>
</div>

> Run your c# code inside VSCode terminal.

## ↓ STEP #1

You will need dotnet framework to run your C# code. You can download & install it from [here](https://dotnet.microsoft.com/download).

## 👨🏻‍💻 STEP #2

Now open your `.bashrc/.zshrc` file and copy-paste the following code inside there.

```sh
# run your c# code inside your terminal
function run() {
    dotnet restore && clear && dotnet run
}
```

## 💥 STEP #3

Now go to your project & open your terminal. Make sure your terminal path is set to your project's path.

Now you can run your C# code anytime with the following command inside VSCode terminal or any other terminal whatsoever.

```sh
run
```

## 👻 AUTHOR

🚀 Aspiring JavaScript developer. 🐼 An MLH ’20 fellow, 👨🏻‍💻 Jr. Dev Advocate @Worwox, 💥 an open-sourcer (authored several open-source tools), 🦉open-source contributor (contributed to the likes of Node.js, Fluid Project, Global Public Inclusive Infrastructure), 🙌 former Google’s Developer Student Clubs Lead, 💻 Beta – Microsoft Learn Student Ambassador, ✍️ Technical Writer, 🗣 Speaker, and 🎸 a Guitarist.

- [Blog](https://msaad.dev)
- [Twitter](https://twitter.com/msaaddev)

## 🔑 LICENSE

- MIT
