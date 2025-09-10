<h1 align="center">🦀 Hadrian Lazic (aka Had2020)</h1>
<h3 align="center">🧬 Rust & Codecraft · I build tools, simulate Digital life, and make CPUs sweat!</h3>

<p align="center">
  <a href="mailto:hadrian.lazic@gmail.com"><img src="https://img.shields.io/badge/Email-hadrian.lazic@gmail.com-red?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/hadrian-lazic-3922b1277"><img src="https://img.shields.io/badge/LinkedIn-Hadrian%20Lazic-blue?style=flat-square&logo=linkedin"/></a>
  <img src="https://img.shields.io/badge/-Rust-orange?style=flat-square&logo=rust">
  <img src="https://img.shields.io/badge/-Low%20Level%20Systems-gray?style=flat-square">
</p>

![Codewars](https://www.codewars.com/users/had2020/badges/large)

```rust
// main.rs - A Rust-powered intro
fn main() {
    let mut dev = Dev::new("Hadrian", Lang::Rust);
    if !dev.has_greeted() {
        dev.greet();
    }
}

#[derive(Debug)]
enum Lang {
    Rust, // My gem!
    JavaScript,
    Python,
    HtmlCss,
}

struct Dev {
    name: &'static str,
    fav_lang: Lang,
    greeted: bool,
}
impl Dev {
    fn new(name: &'static str, fav_lang: Lang) -> Self {
        Self { name, fav_lang, greeted: false }
    }
}
trait Greeter {
    fn greet(&mut self);
    fn has_greeted(&self) -> bool;
}
impl Greeter for Dev {
    fn greet(&mut self) {
        println!("Hello, world! I'm {} and I thrive in {:?}", self.name, self.fav_lang);
        self.greeted = true;
    }
    fn has_greeted(&self) -> bool { self.greeted }
}
```

---

<div align="center">
  <a href="https://github.com/had2020">
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=had2020&layout=compact&hide=html,javascript,makefile,fluent,css&theme=radical" alt="Most Used Languages" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=had2020&show_icons=true&include_all_commits=true&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&theme=radical" alt="GitHub Stats" />
  </a>
</div>

---

### **Areas of Interest**

<p align="center"> <kbd>🦀 Rust</kbd> <kbd>⚙️ Low-level systems</kbd> <kbd>🧠 AI/ML</kbd> <kbd>☁️ Cluster computing</kbd> <kbd>🧬 DNA simulation</kbd> <kbd>Solana </kbd> </p>

---

### **You can Reach me at**
> ✉️ <b>Email:</b> <a href="mailto:hadrian.lazic@gmail.com">hadrian.lazic@gmail.com</a>

> 💼 <b>LinkedIn:</b> <a href="https://www.linkedin.com/in/hadrian-lazic-3922b1277">Hadrian Lazic</a>
