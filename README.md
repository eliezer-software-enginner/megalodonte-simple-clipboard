# Simple Clipboard

Uma biblioteca Java simples e leve para manipulação de **Clipboard (área de transferência)** para projetos **Megalodonte**, com foco em **arquitetura limpa**, **testabilidade** e **facilidade de uso**.

---

## ✨ Objetivo

O objetivo do **simple-clipboard** é fornecer uma API mínima e confiável para:
- Copiar texto para o clipboard
- Ler texto do clipboard

---

## 📦 Instalação (Maven Local)

Após publicar a lib localmente:

```bash
./gradlew publishToMavenLocal
```

Adicione ao seu projeto:

```gradle
repositories {
    mavenLocal()
    mavenCentral()
}

dependencies {
    implementation("megalodonte:simple-clipboard:1.0.0")
}
```

---

## 📦 Instalação (Via Jitpack)

Adicione ao seu projeto:

```gradle
// settings.gradle.kts ou build.gradle.kts
repositories {
    mavenCentral()
    maven { url = uri("https://jitpack.io") }
}

// build.gradle.kts
dependencies {
    implementation("com.github.eliezer-software-enginner:simple-clipboard:1.0.0")
}
```

---

## 🚀 Uso Básico

```java
import megalodonte.Clipboard;

Clipboard.setString("Olá mundo");

String texto = Clipboard.getString();
System.out.println(texto);
```

---

---

## 📜 Licença

MIT License

---

## 👨‍💻 Autor

Projeto desenvolvido por **[Eliezer](https://github.com/eliezer-software-enginner)**.