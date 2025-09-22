# Módulo Contábil 📊

Sistema acadêmico em **Java (Swing)** para **cálculo de impostos** como **IPI** e **PIS**, aplicando **POO**, herança e boas práticas de organização de código.

<p align="left">
  <img alt="Java" src="https://img.shields.io/badge/Java-8%2B-orange">
  <img alt="Build" src="https://img.shields.io/badge/build-Ant%20%7C%20Maven-blue">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-success">
</p>

---

## ✨ Funcionalidades
- Cálculo de **IPI** (Imposto sobre Produtos Industrializados)
- Cálculo de **PIS** (Programa de Integração Social)
- Modelagem orientada a objetos (classe base **Imposto** e especializações)
- Interface desktop simples (Swing)

---

## 🧰 Tecnologias
- Java 8+ (POO, Swing)
- NetBeans/Ant (ou Maven, se aplicável)

---

## ⚙️ Como executar

> **Dica:** publique quaisquer **.zip/.jar** em **Releases**; mantenha o **código-fonte descompactado** no repositório para melhor visualização.

### 1) Pré-requisitos
- **Java 8+**
- IDE (**NetBeans** recomendado)

### 2) Abrir o projeto
- Extraia o código-fonte (se estiver em `.zip`) para a **raiz do repositório**.
- Abra o projeto no **NetBeans**.

### 3) Executar
- Compile e execute a classe principal (ex.: `ModuloContabil.java`).

---

## 📁 Estrutura sugerida
```
/README.md
/LICENSE
/.gitignore
/.github/workflows/build.yml
/src/modulo/contabil/
  Imposto.java
  IPI.java
  PIS.java
  ModuloContabil.java
nbproject/            # se NetBeans/Ant
pom.xml               # se Maven
```
> Mantenha apenas **código-fonte e configs** no versionamento. Binários e zips devem ir nas **Releases**.

---

## 🧪 CI (GitHub Actions)
Workflow de exemplo para compilar com **Ant** (se `build.xml` existir) ou **Maven** (se `pom.xml` existir) e validar o build em **Java 8** e **17**.

---

## 📝 Licença
Distribuído sob a licença **MIT**. Veja `LICENSE` para detalhes.
