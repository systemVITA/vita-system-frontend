# Vita-System
sistema de controle e plataforma de recebimento de dados do VITA


# Projeto VITA - Monitoramento e Controle de Dispositivo Médico

![VITA Logo](logo.png)(sem logo// AINDA)

O Projeto VITA é uma iniciativa que visa desenvolver um sistema embarcado inovador para o monitoramento e controle de dispositivos médicos, utilizando tecnologias de Internet das Coisas (IoT) e integração de hardware e software. O objetivo central é permitir um acompanhamento eficiente de dispositivos médicos, fornecendo uma interface gráfica amigável para visualização em tempo real, além de comunicação segura com um banco de dados para análise posterior.

## Características Principais

- Monitoramento em Tempo Real: Através da comunicação bidirecional entre o dispositivo médico e a interface web, os dados são apresentados em tempo real, possibilitando um acompanhamento preciso.

- Controle Remoto: O sistema permite o controle remoto do dispositivo médico por meio da interface gráfica, possibilitando ajustes em parâmetros e configurações.

- Armazenamento de Dados: Os dados coletados são armazenados de forma segura em um banco de dados ou arquivo CSV, permitindo análises futuras e a geração de relatórios.

- Tecnologias de Ponta: Utilização de protocolos MQTT e HTTP para a comunicação entre o hardware e a interface web, demonstrando o uso de tecnologias avançadas.

## Como Utilizar

1. **Instalação:**
   - Clone este repositório em sua máquina local.
   - Instale as dependências necessárias listadas no arquivo `requirements.txt`.

2. **Configuração:**
   - Siga as instruções na documentação do projeto para configurar o Access Point no Arduino Wi-Fi R2.

3. **Execução:**
   - Execute o servidor da interface gráfica executando o comando `python app.py`.
   - Acesse a interface web no navegador utilizando o endereço `http://localhost:3000`.

4. **Utilização:**
   - Visualize os dados em tempo real na interface gráfica.
   - Faça ajustes e controle o dispositivo médico remotamente.

## Contribuição

Contribuições são bem-vindas! Se você encontrou algum bug ou tem alguma sugestão de melhoria, por favor, abra uma issue ou envie um pull request.

## Créditos

Este projeto foi desenvolvido por Nerval Junior e faz parte de um trabalho acadêmico/pesquisa. Para mais informações, consulte os documentos e referências mencionados.

### ⚡️ Backend
- FastAPI
- Flask
- MongoDB


### 🎨 Frontend
-next.js
- React.js



### 📄 License
MIT

Este projeto é licenciado sob a [Licença MIT](LICENSE).




This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.



