# Hey👋, I'm sudokit

```rust
struct Person {
    username: String,
    location: String,
    age: i32,
    languages: Vec<String>,
    ides: Vec<String>,
    interests: Vec<String>,
    other_info: String,
}

fn main() {
    let sudokit: Person = Person {
	    username: String::from("sudokit"),
        location: String::from("Finland"),
		age: 17,
		languages: vec![ "Python", "C++ (learned the bare basics)", "C (learned the bare basics)", "Rust (still learning)" ].iter().map(|&s| s.into()).collect(),
		ides: vec![ "CLion", "VSCode", "Nvim", "Neovide (current editor)" ].iter().map(|&s| s.into()).collect(),
		interests: vec![ "Physics engines (especially voxel)", "3D/2D rendering engines (especially voxel)", "Arduino related stuff", "Linux", "Windows" ].iter().map(|&s| s.into()).collect(),
		other_info: String::from("Iv used windows for 1 year but now im using linux for 1 year and i think im going to stick to using linux."),
	};
    println!("Hi 👋. I'm {}, {} years old.", sudokit.username, sudokit.age);
    println!("Programming languages iv used are: ");
    for language in sudokit.languages.iter() {
        println!("* {language}");
    }
    println!("\nIDEs i have experience with are: ");
    for ide in sudokit.ides.iter() {
        println!("* {ide}");
    }
    println!("\nTechnologies im interested in include: ");
    for interest in sudokit.interests.iter() {
        println!("* {interest}");
    }
    println!("\n{}", sudokit.other_info);
}
```
```
~/githubreadme on master 
> cargo run
```

Hi 👋. I'm sudokit, 17 years old.
Programming languages iv used are:
* Python [![Python](https://img.shields.io/badge/Python-yellow?style=flat-square&logo=Python)](https://www.python.org/) (used for 1 year but still learning)
* C++ [![C++](https://img.shields.io/badge/C++-blue?style=flat-square&logo=C++)](https://isocpp.org/) (learned the bare basics and still learning)
* C [![C](https://img.shields.io/badge/C-gray?style=flat-square&logo=C)](https://en.wikipedia.org/wiki/C_(programming_language)) (learned the bare basics)
* Rust [![Rust](https://img.shields.io/badge/Rust-red?style=flat-square&logo=rust)](https://www.rust-lang.org/) (still learning)

IDEs i have experience with are: 
* CLion [![CLion](https://img.shields.io/badge/CLion-aqua?style=flat-square&logo=JetBrains)](https://www.jetbrains.com/clion/)
* VSCode [![VSCode](https://img.shields.io/badge/VSCode-blue?style=flat-square&logo=Microsoft)](https://code.visualstudio.com/)
* Neovim [![Neovim](https://img.shields.io/badge/Neovim-brightgreen?style=flat-square&logo=Neovim)](https://neovim.io/)
* Neovide [![Neovide](https://img.shields.io/badge/Neovide-brightgreen?style=flat-square&logo=Neovim)](https://neovide.dev/)

Technologies im interested in include: 
* Physics engines (especially voxels)
* 3D/2D rendering engines (especially voxels)
* Arduino related stuff [![Arduino](https://img.shields.io/badge/Arduino-blue?style=flat-square&logo=Arduino)](https://www.arduino.cc/)
* Linux[![Linux](https://img.shields.io/badge/Linux-black?style=flat-square&logo=Linux)](https://www.linux.org/)
* Windows [![Windows](https://img.shields.io/badge/Windows-blue?style=flat-square&logo=Windows)](https://www.microsoft.com/en-us/windows) 

Iv used windows for 1 year but now im using linux for 1 year and i think im going to stick to linux.


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sudokit&show_icons=true&theme=tokyonight)
