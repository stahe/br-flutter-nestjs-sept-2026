# Um exemplo cliente/servidor - Flutter / NestJS (2026)

Este repositório refere-se ao curso **"Um exemplo cliente/servidor - Flutter / NestJS (2026)"**, publicado em:

**https://stahe.github.io/br-flutter-nestjs-sept-2026/**

## Visão geral

Este documento adapta o aplicativo didático **RdvMedecins** (agendamento de consultas médicas) — já abordado nos cursos de Angular, React e Vue.js — para as tecnologias atuais. Aqui ele apresenta uma versão mobile: um cliente **Flutter** (Dart) que se apoia em um servidor **NestJS** (TypeScript) que expõe uma API JSON protegida por autenticação JWT (papéis ADMIN / USER).

Este documento destina-se a leitores que já conhecem pelo menos um framework web (Angular, React ou Vue.js) e estão aprendendo Flutter por comparação: cada conceito do Flutter é relacionado ao seu equivalente nesses frameworks.

O curso aborda:

- a configuração do ambiente de desenvolvimento (VSCode, SDK do Flutter, Android Studio, SDK do Android, preparação de um celular Android e de um emulador, `flutter doctor`);
- a instalação e a execução do servidor NestJS do aplicativo (banco de dados MySQL, configuração, testes com um navegador e com o Postman);
- uma introdução ao Flutter (widgets, `StatelessWidget`/`StatefulWidget`, gerenciamento de estado com `provider`, a linguagem Dart);
- um passo a passo detalhado, arquivo por arquivo, do cliente Flutter do aplicativo RdvMedecins;
- a portabilidade do mesmo código-fonte para três famílias de destino: mobile (Android/iOS), desktop (Windows/macOS/Linux) e web, tratando dos desafios específicos do mobile (endereço do servidor, tráfego HTTP não criptografado, telas estreitas);
- uma conclusão sobre o que foi construído e caminhos para evoluções futuras.

## Autores

- **Autora principal:** IA Claude (Anthropic)
- **Revisor:** Serge Tahé
