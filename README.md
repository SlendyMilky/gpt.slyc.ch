<h1 align="center"><b>Better ChatGPT</b></h1>

<p align="center">
    <a href="https://gpt.slyinc.ch" target="_blank"><img src="public/apple-touch-icon.png" alt="Better ChatGPT" width="100" /></a>
</p>

<h4 align="center"><b>Free, Powerful, Limitless, Intelligent, Engaging</b></h4>

<p align="center">
<a href="https://github.com/SlendyMilky/gpt.slyinc.ch/blob/main/LICENSE" target="_blank">

<p align="center">
    <a href="https://gpt.slyinc.ch">Enter Website</a>
    ·
    <a href="https://github.com/SlendyMilky/gpt.slyinc.ch/issues/new/choose">Report Bug</a>
</p>


## 👋🏻 Introducing Better ChatGPT

<p align="center">
    <a href="https://gpt.slyinc.ch" target="_blank">
        <img src="assets/preview.png" alt="landing" width=500 />
    </a>
</p>

Are you ready to unlock the full potential of ChatGPT with Better ChatGPT?

Better ChatGPT is the ultimate destination for anyone who wants to experience the limitless power of conversational AI. With no limits and completely free to use for all, our app harnesses the full potential of OpenAI's ChatGPT API to offer you an unparalleled chatbot experience.

Whether you're looking to chat with a virtual assistant, improve your language skills, or simply enjoy a fun and engaging conversation, our app has got you covered. So why wait? Join us today and explore the exciting world of Better ChatGPT!

# 🔥 Features

Better ChatGPT comes with a bundle of amazing features! Here are some of them:

- Proxy to bypass ChatGPT regional restrictions
- Prompt library
- Organize chats into folders (with colours)
- Filter chats and folders
- Token count and pricing
- ShareGPT integration
- Custom model parameters (e.g. presence_penalty)
- Chat as user / assistant / system
- Edit, reorder and insert any messages, anywhere
- Chat title generator
- Save chat automatically to local storage
- Import / Export chat
- Download chat (markdown / image / json)
- Sync to Google Drive
- Azure OpenAI endpoint support
- Multiple language support (i18n)

# 🛠️ Usage

To get started, simply visit our website at <https://gpt.slyinc.ch/>. There are 3 ways for you to start using Better ChatGPT.


### Features:

- Unlimited local storage
- Runs locally (access Better ChatGPT even if the website is not accessible)

# 🛫 Host your own Instance

If you'd like to run your own instance of Better ChatGPT, you can easily do so by following these steps:

## Vercel

One click deploy with Vercel

[![Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SlendyMilky/gpt.slyinc.ch)

## GitHub Pages

### Steps

1. Create a GitHub account (if you don't have one already)
2. Fork this [repository](https://github.com/SlendyMilky/gpt.slyinc.ch)
3. In your forked repository, navigate to the `Settings` tab
   ![image](https://user-images.githubusercontent.com/59118459/223753577-9b6f8266-26e8-471b-8f45-a1a02fbab232.png)
4. In the left sidebar, click on `Pages` and in the right section, select `GitHub Actions` for `source`.
   ![image](https://user-images.githubusercontent.com/59118459/227568881-d8fb7baa-f890-4dee-8fc2-b6b429ba2098.png)
5. Now, click on `Actions`
   ![image](https://user-images.githubusercontent.com/59118459/223751928-cf2b91b9-4663-4a36-97de-5eb751b32c7e.png)
6. In the left sidebar, click on `Deploy to GitHub Pages`
   ![image](https://user-images.githubusercontent.com/59118459/223752459-183ec23f-72f5-436e-a088-e3386492b8cb.png)
7. Above the list of workflow runs, select `Run workflow`.
   ![image](https://user-images.githubusercontent.com/59118459/223753340-1270e038-d213-4d6f-938c-66a30dad7c88.png)
8. Navigate back to the `Settings` tab
   ![image](https://user-images.githubusercontent.com/59118459/223753577-9b6f8266-26e8-471b-8f45-a1a02fbab232.png)
9. In the left sidebar, click on `Pages` and in the right section. Then at the top section, you can see that "Your site is live at `XXX`".
   ![image](https://user-images.githubusercontent.com/59118459/227568881-d8fb7baa-f890-4dee-8fc2-b6b429ba2098.png)

### Running it locally

1. Ensure that you have the following installed:

   - [node.js](https://nodejs.org/en/) (v14.18.0 or above)
   - [yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/) (6.14.15 or above)

2. Clone this [repository](https://github.com/SlendyMilky/gpt.slyinc.ch) by running `git clone https://github.com/SlendyMilky/gpt.slyinc.ch.git`
3. Navigate into the directory by running `cd BetterChatGPT`
4. Run `yarn` or `npm install`, depending on whether you have yarn or npm installed.
5. Launch the app by running `yarn dev` or `npm run dev`

### Running it locally using docker compose
1. Ensure that you have the following installed:

   - [docker](https://www.docker.com/) (v24.0.7 or above)
      ```bash
      curl https://get.docker.com | sh \
      && sudo usermod -aG docker $USER
      ```

2. Build the docker image
   ```
   docker compose build
   ```

3. Build and start the container using docker compose
   ```
   docker compose build
   docker compose up -d
   ```

4. Stop the container
   ```
   docker compose down
   ```