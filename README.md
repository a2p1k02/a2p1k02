<h1 align="center">Hi 👋, I'm Alexander</h1>
<h3 align="center">I'm a software engineer</h3>
<h3 align="center">I'm into the Rust and C++ programming languages </h3><br>

<p align="center">
  <a href="https://github.com/a2p1k02?tab=repositories">
    <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=a2p1k02&theme=material-palenight&show_icons=true&rank_icon=github" />
    <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=a2p1k02&layout=compact&langs_count=8&card_width=320&theme=material-palenight&show_icons=true" />
  </a>
</p>

<h3 align="center">Connect with me:</h3>
<p align="center">
  <a href="https://discord.gg/a2p1k02#2340" target="blank"><img align="center" src="https://img.icons8.com/?size=100&id=61604&format=png&color=000000" alt="a2p1k02#2340" height="50" width="50"/></a>
  <a href="https://t.me/a2p1k02" target="blank"><img align="center" src="https://img.icons8.com/?size=100&id=114954&format=png&color=000000" alt="a2p1k02#2340" height="50" width="50"/></a>
</p>

<h3 align="center">Other tools:</h3>
<p align="center">
  <a href="https://www.rust-lang.org/" target="_blank"><img src="https://img.icons8.com/?size=100&id=t7vIvDXazOGO&format=png&color=000000" alt="rust" width="50" height="50"/></a>
  <a href="https://www.linux.org/" target="_blank"><img src="https://img.icons8.com/?size=100&id=104289&format=png&color=000000" alt="linux" width="50" height="50"/></a>
  <a href="https://en.cppreference.com/w/" target="_blank"><img src="https://img.icons8.com/?size=100&id=mciovJOS9Auv&format=png&color=000000" alt="c++" width="50" height="50"/></a>
</p>

```rust
fn main() {
    let hello = [72, 101, 108, 108, 111, 44, 32, 87, 111, 114, 108, 100, 33]
        .iter()
        .map(|&c| c as u8 as char)
        .collect::<String>();
    println!("{}", hello);
}
```

```cpp
#include <iostream>

int main() {
    char encoded[] = {89, 126, 125, 125, 126, 27, 15, 104, 126, 109, 125, 115, 18};
    for (char c : encoded) {
        std::cout << static_cast<char>(c ^ 0x1F);
    }
    std::cout << std::endl;
    return 0;
}
```
