🇧🇷 Português | 🇺🇸 [Inglês](README.md)

# 📱 Calculadora de IMC (Android)

Aplicativo Android simples para cálculo de IMC (Índice de Massa Corporal), desenvolvido em Kotlin. O app permite inserir o peso, ajustar a altura com um controle deslizante e obter o resultado de forma rápida e intuitiva.

---

## 🚀 Funcionalidades

* Inserção de **peso** via campo de texto
* Seleção de **altura** usando um `SeekBar` (em centímetros)
* Exibição dinâmica da altura selecionada
* Cálculo automático do **IMC**
* Resultado formatado com duas casas decimais
* Validação de entrada:

  * Aviso caso o peso seja inválido
  * Aviso caso a altura seja inválida
* Botão para **limpar todos os campos**
* Interface simples e direta

---

## 🧮 Fórmula utilizada

O cálculo do IMC segue a fórmula padrão:

```
IMC = peso / (altura * altura)
```

> A altura é convertida de centímetros para metros antes do cálculo.

---

## 🖥️ Interface

O app contém os seguintes elementos:

* Campo de entrada para peso
* Barra deslizante (SeekBar) para altura
* Texto que mostra a altura selecionada
* Botão **Calcular**
* Botão **Limpar**
* Área de exibição do resultado

---

## ⚠️ Tratamento de erros

O aplicativo trata erros comuns para melhorar a experiência do usuário:

* Caso o campo de peso esteja vazio ou inválido → exibe um `Toast`
* Caso a altura seja igual a zero → exibe um `Toast`
* Evita crashes com uso de `try/catch`

---

## 🧹 Botão Limpar

Ao clicar em **Limpar**, o app:

* Apaga o peso digitado
* Reseta a altura para 0
* Esconde o valor da altura
* Esconde o resultado do IMC

---

## 🛠️ Tecnologias utilizadas

* Kotlin
* Android SDK
* XML (layout)
* Componentes Android:

  * `EditText`
  * `SeekBar`
  * `TextView`
  * `Button`
  * `Toast`

---

## 📌 Observações

* A altura é selecionada em centímetros e convertida internamente para metros
* O resultado exibido segue o padrão: `IMC: XX.XX`
* Interface otimizada para simplicidade e uso rápido

---

## 📄 Licença

Este projeto é livre para uso e modificação para fins de estudo.

--
