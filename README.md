# Olá! Eu sou o Rodrigo Salgado 👋

<div align="center">
  <a href="https://github.com/salgadu">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=salgadu&show_icons=true&theme=light&include_all_commits=true&count_private=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=salgadu&layout=compact&langs_count=7&theme=light"/> 
  </a>
</div>
  
<div style="display: inline_block"><br>
  <img align="center" alt="Fedora" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fedora/fedora-original.svg">
  <img align="center" alt="Flutter" height "30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg">
  <img align="center" alt="Vanilla JS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Svelte" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/svelte/svelte-original.svg">
  <img align="center" alt="Unity" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/unity/unity-original.svg">
  <img align="center" alt="C/C++" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-plain.svg">
  <img align="center" alt="Docker" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
</div>
  
##

<div>
  <a href="https://www.linkedin.com/in/salgadu" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>

<div align=center>
  <h3><b>Profile Visitor Count</b></h3>
</div>
    
<p align="center" >   
  <img src="https://profile-counter.glitch.me/victormoreiraofc/count.svg" />  
</p>

```C
#include <stdio.h>
#include <string.h>

// Define the Desenvolvedor structure
struct Desenvolvedor {
    char nome[50];
    char area[50];
    char trabalho[50];
    char local[50];
    char* linguagens[50];
    char* bibliotecas[50];
    char* frameworks[50];
};

int main() {
    // Create instances of the Desenvolvedor structure
    struct Desenvolvedor SobreMim;
    struct Desenvolvedor Skills;

    // Initialize the SobreMim instance
    strcpy(SobreMim.nome, "Seu nome");
    strcpy(SobreMim.area, "Sua área");
    strcpy(SobreMim.trabalho, "Onde trabalha");
    strcpy(SobreMim.local, "Local");

    // Initialize the Skills instance
    SobreMim.linguagens[0] = "Suas linguagens";
    SobreMim.bibliotecas[0] = "Suas bibliotecas";
    SobreMim.frameworks[0] = "Seus frameworks";

    // Print the information
    printf("Sobre Mim:\n");
    printf("Nome: %s\n", SobreMim.nome);
    printf("Área: %s\n", SobreMim.area);
    printf("Trabalho: %s\n", SobreMim.trabalho);
    printf("Local: %s\n", SobreMim.local);

    printf("\nSkills:\n");
    printf("Linguagens: %s\n", SobreMim.linguagens[0]);
    printf("Bibliotecas: %s\n", SobreMim.bibliotecas[0]);
    printf("Frameworks: %s\n", SobreMim.frameworks[0]);

    return 0;
}


```
