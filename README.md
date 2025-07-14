# Sorteio App

Aplicativo Android simples para sortear um número aleatório entre 0 e 10.

## Tecnologias e Bibliotecas

- **Linguagem:** Java (Android)
- **SDK:** Android SDK 24+ (target/compileSdk: 34)
- **Bibliotecas Utilizadas:**
  - [androidx.appcompat:appcompat:1.7.0](https://developer.android.com/jetpack/androidx/releases/appcompat)
  - [com.google.android.material:material:1.12.0](https://maven.google.com/web/index.html?q=com.google.android.material#com.google.android.material:material)
  - [androidx.activity:activity:1.9.3](https://developer.android.com/jetpack/androidx/releases/activity)
  - [androidx.constraintlayout:constraintlayout:2.2.0](https://developer.android.com/jetpack/androidx/releases/constraintlayout)
  - **Testes:** 
    - [junit:junit:4.13.2](https://junit.org/junit4/)
    - [androidx.test.ext:junit:1.2.1](https://developer.android.com/jetpack/androidx/releases/test)
    - [androidx.test.espresso:espresso-core:3.6.1](https://developer.android.com/jetpack/androidx/releases/espresso)

## Padrões de Projeto

- **MVC Simples:** A lógica está concentrada na `MainActivity`, separando interface (XML) e código.
- **ConstraintLayout:** Utilizado para a interface responsiva.
- **Edge-to-Edge**: Uso do `EdgeToEdge` para melhor aproveitamento da tela em dispositivos modernos.

## Como rodar o projeto

1. **Pré-requisitos:**
   - [Android Studio](https://developer.android.com/studio) instalado
   - JDK 11 ou superior

2. **Clonando o projeto:**
   ```sh
   git clone <url-do-repositorio>
   ```

3. **Abrindo no Android Studio:**
   - Selecione `Open an existing project` e escolha a pasta `Sorteio-App`.

4. **Build e execução:**
   - Aguarde o download das dependências.
   - Conecte um dispositivo ou use um emulador.
   - Clique em **Run** (ou Shift+F10).

## Configurações importantes

- **Mínimo SDK:** 24 (Android 7.0)
- **Target SDK:** 34
- **ProGuard:** Desativado por padrão para build release.
- **Gerenciamento de dependências:** Via Gradle com catálogos de versões (`libs.versions.toml`).

---

by Rodolfo M F Abreu