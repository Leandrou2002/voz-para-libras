# Voz para Libras — Speech-to-Text com Tradução para Libras

O **Voz para Libras** é um projeto desenvolvido como **desafio de projeto** do bootcamp  
**Bradesco – GenAI & Dados**, oferecido pela **DIO (Digital Innovation One)**.

A aplicação demonstra, de forma prática, como utilizar **Inteligência Artificial Generativa** para transformar fala em texto e promover **acessibilidade digital**, integrando reconhecimento automático de voz com tradução para **Libras**.

---

## Acesse o Projeto (Google Colab)

O projeto pode ser testado diretamente no Google Colab pelo link abaixo:

👉 **[Abrir notebook no Google Colab](https://colab.research.google.com/drive/14Br7PIMy_mvo4sZJztoMyFQKjaekluRg?usp=sharing)**

> Recomenda-se executar o notebook e abrir a aplicação em **nova guia**, conforme instruções exibidas no próprio Colab.

---

## Intenção do Projeto

O objetivo do **Voz para Libras** é:

- Aplicar **IA generativa** em um cenário real;
- Utilizar o **Whisper (OpenAI)** para reconhecimento de fala em português;
- Integrar o texto transcrito ao **VLibras**, ampliando o acesso à informação para pessoas surdas;
- Demonstrar a integração entre **Python (backend)** e **frontend web** dentro do **Google Colab**;
- Atender aos requisitos de um **desafio prático de bootcamp**, indo além de um exemplo teórico.

---

## Visão Geral da Solução

O funcionamento do sistema segue o fluxo abaixo:

1. O usuário grava sua voz diretamente pelo navegador.
2. O áudio é enviado para um backend desenvolvido em Python.
3. O Whisper realiza a transcrição automática da fala para texto.
4. O texto transcrito é exibido automaticamente na interface.
5. O usuário pode selecionar o texto e utilizar o **VLibras** para visualizar a tradução em Libras por meio de um avatar animado.

Todo o processo ocorre de forma integrada e automatizada.

---

## Tecnologias Utilizadas

### Backend
- Python
- Whisper (OpenAI) — modelo `small`
- Flask
- FFmpeg
- Google Colab Runtime

### Frontend
- HTML5
- CSS3
- JavaScript
- MediaRecorder API
- VLibras (Widget Oficial)

---

## ⚠️ Observações Importantes

- O Google Colab utiliza domínios temporários.  
  Por isso, ao fechar e reabrir o notebook, o navegador pode solicitar novamente a permissão de uso do microfone.

---

## Contexto do Bootcamp

Este projeto faz parte do bootcamp **Bradesco – GenAI & Dados**, da **DIO**, cujo objetivo é capacitar profissionais no uso prático de **Inteligência Artificial Generativa**, **dados** e **soluções modernas aplicadas a problemas reais**.

---

## Conclusão

O **Voz para Libras** demonstra como a Inteligência Artificial pode ser aplicada para promover **inclusão e acessibilidade**, utilizando ferramentas modernas e uma arquitetura simples, porém funcional, mesmo dentro das limitações do Google Colab.

O projeto serve como **atividade de bootcamp**, **prova de conceito** e **material de portfólio**, com potencial para evoluções futuras.
