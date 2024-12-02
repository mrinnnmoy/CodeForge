# CodeForge

Smart Contract Copilot for Blockchain Development.

## ⚠️ Problem to Solve.

Developing smart contracts and decentralized applications (dApps) can be challenging, especially for new developers or those working with unfamiliar codebases. Writing secure, efficient code often requires extensive knowledge of blockchain-specific languages and patterns. Additionally, understanding existing contracts can be time-consuming and difficult.

There’s a need for a platform that helps developers by generating boilerplate code, offering real-time code suggestions and simplifying the understanding of existing smart contracts.

## ✅ Possible Solution.

**CodeForge** is a smart contract assistant powered by large language models (LLMs) like GPT-3. It aims to simplify the development of smart contracts by:

1. **Real-time Autocomplete**: Offering code suggestions and completions while developers write their smart contracts, similar to how GitHub Copilot works for general programming.
   
2. **Boilerplate Code Generation**: Automatically generating boilerplate code for common smart contract patterns (e.g., token contracts, DAO governance contracts).
   
3. **Code Understanding Assistance**: Providing human-readable summaries and explanations for existing smart contracts, helping developers understand how they work and whether they are secure.

4. **Security Best Practices**: Suggesting code improvements that follow best practices in smart contract development to ensure security and efficiency.

## ⚙️ Architecture.

![Working Architecture](./)
[Excalidaw File...](./)

## 🛠 Tools, Languages & Frameworks used.

- **ReactJS**: Frontend library for building interactive user interfaces.
- **Node.js**: Backend runtime environment for server-side JavaScript.
- **Express.js**: Web framework for building RESTful APIs on Node.js.
- **Solidity**: Smart contract language to build Ethereum-based contracts.
- **OpenAI GPT-3**: Large language model for code generation and understanding.
- **Ethereum**: Blockchain platform for deploying and interacting with smart contracts.
- **IPFS**: Decentralized storage for contract metadata, descriptions and documentation.

## 📂 Folder Structure.

* **client**: Contains the frontend codebase.
* **server**: Contains backend code and smart contract templates.

## 🧑‍💻 Contributions to this repo are WELCOME.👋

* 🎨 Any improvements to the design and UI are welcome.
* 🔨 Try to break the website by testing it to find any bugs. If you find any, check if there is an issue already open for it, if there is none, then report it.

## 🔃 Steps to be followed in order to make valid contributions to this repo.

**1.** Fork the [CodeForge](https://github.com/mrinnnmoy/CodeForge) repo by clicking on the fork button on the top of the page. This will create a copy of this repository in your account.

**2.** Clone the forked repository

        git clone "https://github.com/<your-github-username>/CodeForge"

* Download and install Node JS v16.16.0
* Download and install Git.
* Go to the terminal of your code editor and run "npm install" to download packages.
* Run "npm run dev" to start a local server.

**3.** Make necessary changes and commit those changes. <br />
Remember never push anything to the Main branch. <br />

Always change your branch to "develop" using:

    git checkout develop

Again check your current branch using:

    git branch

It should point \*develop

Now add your changes using:

    git add files-you-edited

If there are multiple files you can use:

    git add .

Now create a commit message using:

    git commit -m "<commit-message-goes-here>"

**4.** Push changes to GitHub

    git push origin develop

**5.** Create a Pull Request 👋<br>

Now you go to your repository on GitHub, you’ll see a `Compare & pull request` button. Click on that button and now write a summary of what changes you have done. (Attach images if required). I will review your code and merge it if it passes all the tests.❤️
