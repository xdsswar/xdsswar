<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2563EB&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+XDSSWAR+%F0%9F%91%8B;Self-Taught+Developer+%E2%80%A2+10%2B+Years;Java+%E2%80%A2+JavaFX+%E2%80%A2+Native+Interop;Building+my+own+language%3A+Jux;Always+learning%2C+always+coding" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://github.com/xdsswar?tab=followers"><img src="https://img.shields.io/github/followers/xdsswar?label=Followers&style=for-the-badge&color=2563EB&labelColor=1f2328" alt="followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=xdsswar&style=for-the-badge&color=2563EB&labelColor=1f2328&label=Profile+Views" alt="profile views" />
  <a href="https://github.com/xdsswar?tab=repositories"><img src="https://img.shields.io/badge/Repositories-350+-2563EB?style=for-the-badge&labelColor=1f2328" alt="repos" /></a>
</p>

---

### 🧠 About Me

> Written in **Jux**, my own language (syntax highlighted as Java, since it's that close):

```java
public class Developer {
    private final String  name;
    private final String  org;
    private final int     years;
    private final boolean learning;

    public Developer() {
        this.name     = "XSS";
        this.org      = "Xtreme Software Solutions (XSS&IT)";
        this.years    = 10;     // self-taught, and counting
        this.learning = true;   // always
    }

    public String[] building() {
        return new String[] {
            "Jux: this very language + its juxc compiler",
            "skia-fx: a GPU-accelerated OpenJFX renderer on Skia",
            "Native libraries & JavaFX tooling for the JVM"
        };
    }

    public String motto() {
        return $"${this.years} years in, still learning, still building.";
    }
}

public void main() {
    final var me = new Developer();
    print(me.motto());   // 10 years in, still learning, still building.
}
```

A bit more, in plain English: I'm happiest at the **high-level / native** boundary, the kind of work that gets called "you can't do that on the JVM" right before I do it. Lately that's meant making **Jux** self-host and giving **skia-fx** a proper macOS/Linux backend.

- 🐧 On **Linux** all day &nbsp;·&nbsp; 🧩 Founder of **Xtreme Software Solutions**. [Come hang out on Discord](https://discord.gg/Au6Em2eFue)
- 💬 Happy to talk **language design, JavaFX internals, GPU rendering, JNI & FFI**. Find me in the Discord.

---

### 🛠️ Tech Stack

Java is home base; everything else is whatever the problem needs.

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,cpp,c,cs,php,js,rust,dart,flutter,mysql,spring,gradle,idea,git,github,linux&theme=light&perline=8" alt="tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaFX-1B6AC6?style=for-the-badge&logo=openjdk&logoColor=white" alt="JavaFX" />
  <img src="https://img.shields.io/badge/JNI-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="JNI" />
  <img src="https://img.shields.io/badge/Panama%20FFI-007396?style=for-the-badge&logo=java&logoColor=white" alt="Panama FFI" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

---

### 🚩 Flagship Work

> My most ambitious projects, now **open-source** and in active development. Here's what I'm building:

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/xdsswar/juxlang">⚡ Jux</a> <img src="https://img.shields.io/badge/public-2563EB?style=flat-square&labelColor=1f2328" alt="public" /> <img src="https://img.shields.io/badge/in%20dev-F59E0B?style=flat-square&labelColor=1f2328" alt="in dev" /></h3>
      <p><b>My own programming language.</b> A statically-typed, Java/C#-flavored language with a working compiler (<code>juxc</code>) written in Rust. It transpiles <code>.jux</code> source to idiomatic, human-readable Rust, then uses <b>Rust's standard library (and any crate) as its own std</b>, surfaced in Jux syntax.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
        <img src="https://img.shields.io/badge/Compiler-2563EB?style=flat-square&labelColor=1f2328" />
        <img src="https://img.shields.io/badge/LSP-2563EB?style=flat-square&labelColor=1f2328" />
        <img src="https://img.shields.io/badge/IntelliJ%20Plugin-2563EB?style=flat-square&labelColor=1f2328" />
      </p>
      <p align="center"><sub>lex &rarr; parse &rarr; resolve &rarr; typecheck &rarr; lower-to-Rust &rarr; native binary.</sub> · <a href="https://github.com/xdsswar/juxlang"><sub><b>View public repo →</b></sub></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/xdsswar/skiafx">🎨 skia-fx</a> <img src="https://img.shields.io/badge/experimental-F59E0B?style=flat-square&labelColor=1f2328" alt="experimental" /></h3>
      <p>A fork of <b>OpenJFX 25</b> that rips out the aging Prism renderer and replaces it with a modern, GPU-first pipeline built on <b><a href="https://skia.org">Skia</a></b>, the engine behind Chrome, Android &amp; Flutter. <b>Drop-in compatible:</b> every <code>javafx.*</code> API is byte-for-byte identical, so your app runs unchanged, just faster. Adds uncapped frame rates, vector SVG, a bgfx-powered 3D scene graph with glTF loading, and a Chromium-based WebView.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
        <img src="https://img.shields.io/badge/Native%20Skia-007396?style=flat-square&labelColor=1f2328" />
        <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" />
        <img src="https://img.shields.io/badge/Direct3D%2012-0078D6?style=flat-square&labelColor=1f2328" />
      </p>
      <p align="center"><sub>Zero-copy GPU rendering, uncapped frame rates. Windows x64 today; macOS &amp; Linux planned.</sub> · <a href="https://github.com/xdsswar/skiafx"><sub><b>View public repo →</b></sub></a></p>
    </td>
  </tr>
</table>

---

### ⚡ Jux: A Closer Look

**Jux** is my own programming language: write code with the comfort of **Java/C# syntax**, and ship the **performance and safety of Rust**. The `juxc` compiler lowers `.jux` source to *idiomatic, human-readable Rust*, then lets `cargo`/`rustc` produce a native binary, so there's no separate runtime, and **Rust's standard library (plus any crate) is Jux's std**, surfaced in Jux syntax.

<table>
<tr><td>

**What makes it fun**

- 🦀 **Inferred borrow checker:** write plain Java-style aliasing & mutation; the compiler infers ownership and borrows for you, cloning *only* when aliasing actually demands it. No `&`, no `mut`, no lifetimes.
- ➕ **Real operator overloading:** `operator+`, `operator==`, `operator string`, `operator hash` lower to genuine `Add` / `PartialEq` / `Display` impls.
- 🪄 **String interpolation:** `$"Hello, ${name}!"`
- 🧱 **Full OOP:** `final`/`abstract` classes, `interface`, `extends`/`implements`, `super(...)`, ctor overloading, statics
- 🧩 **Records & C#-style properties:** `record Point(int x, int y)`, `{ get; set; }`
- 🧬 **Generics** (bounded & const) · **pattern matching** & exhaustive `enum`s
- 🛟 **Nullable types:** `Node? peer` with the `!!` non-null assertion
- 📦 **`import rust.std.*`:** pull in real Rust crates, called in Jux syntax

</td><td>

```java
import rust.std.PathBuf;             // Rust's std IS Jux's std

public class Money {
    public int cents;
    public Money(int cents) { this.cents = cents; }

    public Money operator+(Money o) {        // -> impl Add
        return new Money(this.cents + o.cents);
    }
    public String operator string() {        // -> impl Display
        return $"$${this.cents}c";
    }
}

public void main() {
    var a = new Money(150);
    var b = new Money(50);

    var sum = a + b;                  // operator+  ->  200c
    print($"sum=$sum, and a is still alive: $a");
    // No manual .clone(), no &, no mut, no lifetimes.
    // The compiler infers all of it. You just write Java.

    var path = new PathBuf();         // std::path::PathBuf::new()
    path.reserve(16);                 // camelCase -> snake_case
}
```

</td></tr>
</table>

> **Pipeline:** `lex → parse → resolve → typecheck → lower-to-Rust → cargo build → native binary`
>
> 👉 **It's open-source:** [github.com/xdsswar/juxlang](https://github.com/xdsswar/juxlang)

---

### 🚀 Open-Source Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">jux-toolkit</h3>
      <p align="center">
        <a href="https://github.com/xdsswar/jux-toolkit">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=xdsswar&repo=jux-toolkit&theme=default&hide_border=false&border_color=d0d7de&bg_color=ffffff&title_color=2563EB&icon_color=2563EB&text_color=1f2328" alt="jux-toolkit" />
        </a>
      </p>
      <p align="center"><sub>Java 25 desktop framework powered by native webviews via Panama FFI. Java meets the web, natively.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">nfx-lib</h3>
      <p align="center">
        <a href="https://github.com/xdsswar/nfx-lib">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=xdsswar&repo=nfx-lib&theme=default&hide_border=false&border_color=d0d7de&bg_color=ffffff&title_color=2563EB&icon_color=2563EB&text_color=1f2328" alt="nfx-lib" />
        </a>
      </p>
      <p align="center"><sub>JavaFX/JNI library for Windows: advanced title bar manipulation & custom window decorations.</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">nfx-icons</h3>
      <p align="center">
        <a href="https://github.com/xdsswar/nfx-icons">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=xdsswar&repo=nfx-icons&theme=default&hide_border=false&border_color=d0d7de&bg_color=ffffff&title_color=2563EB&icon_color=2563EB&text_color=1f2328" alt="nfx-icons" />
        </a>
      </p>
      <p align="center"><sub>A crisp, scalable icon library for JavaFX UIs.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">javafx-spring-demo</h3>
      <p align="center">
        <a href="https://github.com/xdsswar/javafx-spring-demo">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=xdsswar&repo=javafx-spring-demo&theme=default&hide_border=false&border_color=d0d7de&bg_color=ffffff&title_color=2563EB&icon_color=2563EB&text_color=1f2328" alt="javafx-spring-demo" />
        </a>
      </p>
      <p align="center"><sub>Clean integration of JavaFX with the Spring Boot ecosystem.</sub></p>
    </td>
  </tr>
</table>

---

### 📊 GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=xdsswar&show_icons=true&hide_border=false&border_color=d0d7de&bg_color=ffffff&title_color=2563EB&icon_color=2563EB&text_color=1f2328&count_private=true&include_all_commits=true" alt="stats" />
  <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xdsswar&layout=compact&hide_border=false&border_color=d0d7de&bg_color=ffffff&title_color=2563EB&text_color=1f2328&langs_count=8" alt="top langs" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=xdsswar&hide_border=false&border=d0d7de&background=ffffff&stroke=d0d7de&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&currStreakNum=1f2328&sideNums=1f2328&sideLabels=1f2328&dates=656d76" alt="streak" />
</p>

---

### 🤝 Connect

<p align="center">
  <a href="https://github.com/xdsswar"><img src="https://img.shields.io/badge/GitHub-1f2328?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>
  <a href="mailto:georda21@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
  <a href="https://discord.gg/Au6Em2eFue"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="discord" /></a>
</p>

<p align="center"><i>⭐ From <a href="https://github.com/xdsswar">xdsswar</a> · 10 years deep, still learning, still building.</i></p>
