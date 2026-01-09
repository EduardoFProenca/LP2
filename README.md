# 🖥️ C# Console Projects

[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://github.com/EduardoFProenca/CSharp-Console-Projects)
[![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)](https://visualstudio.microsoft.com/)

> Coleção de projetos em C# desenvolvidos no **Visual Studio** durante o curso de **Análise e Desenvolvimento de Sistemas** na **Fatec**, focando em lógica de programação, orientação a objetos e algoritmos fundamentais.

---

## 📖 Sobre

Este repositório contém aplicações console em **C#** desenvolvidas no **Visual Studio** que demonstram conceitos fundamentais de programação, incluindo:

- Operações matemáticas e cálculos geométricos
- Métodos e funções
- Classes e Orientação a Objetos
- Estruturas de controle e repetição
- Entrada e saída de dados
- Boas práticas de código

Todos os projetos foram desenvolvidos como exercícios práticos das disciplinas de programação na Fatec.

---

## 🗂️ Estrutura do Repositório

```
CSharp-Console-Projects/
│
├── Pcalc/                     # Calculadora com operações básicas
│   ├── Program.cs
│   ├── Pcalc.csproj
│   └── README.md
│
├── Ptriangulo/                # Cálculos com triângulos
│   ├── Program.cs
│   ├── Triangulo.cs
│   ├── Ptriangulo.csproj
│   └── README.md
│
├── PtesteMetodos/             # Exercícios com métodos e funções
│   ├── Program.cs
│   ├── Metodos.cs
│   ├── PtesteMetodos.csproj
│   └── README.md
│
├── PClasses/                  # Introdução a POO e Classes
│   ├── Program.cs
│   ├── MinhasClasses.cs
│   ├── PClasses.csproj
│   └── README.md
│
├── Pvolume/                   # Cálculo de volume de sólidos
│   ├── Program.cs
│   ├── Volumes.cs
│   ├── Pvolume.csproj
│   └── README.md
│
└── README.md                  # Este arquivo
```

---

## 🎯 Projetos Disponíveis

### 🧮 **1. Pcalc - Calculadora**
**Funcionalidades:**
- Operações básicas: soma, subtração, multiplicação, divisão
- Validação de entrada
- Interface interativa com menu

**Conceitos aplicados:**
- Métodos e parâmetros
- Estruturas de decisão (if/else, switch)
- Tratamento de exceções
- Validação de divisão por zero

**Como executar:**
1. Abra `Pcalc.sln` no Visual Studio
2. Pressione `F5` ou clique em "Iniciar"

---

### 📐 **2. Ptriangulo - Cálculos com Triângulos**
**Funcionalidades:**
- Verifica se três lados formam um triângulo válido
- Classifica tipo de triângulo (equilátero, isósceles, escaleno)
- Calcula perímetro e área
- Valida entrada de dados

**Conceitos aplicados:**
- Condições matemáticas (teorema de existência)
- Estruturas condicionais encadeadas
- Fórmula de Heron para área
- Validação de dados

**Exemplo de uso:**
```
Digite o lado A: 5
Digite o lado B: 5
Digite o lado C: 5

✓ Forma um triângulo válido
Tipo: Equilátero
Perímetro: 15
Área: 10.83
```

---

### ⚙️ **3. PtesteMetodos - Exercícios com Métodos**
**Funcionalidades:**
- Demonstra diferentes tipos de métodos
- Métodos com e sem retorno
- Métodos com parâmetros
- Sobrecarga de métodos (overload)
- Métodos estáticos vs instância

**Conceitos aplicados:**
- Declaração e chamada de métodos
- Tipos de retorno (void, int, double, string)
- Passagem de parâmetros por valor
- Escopo de variáveis
- Modularização de código

**Exemplo de métodos:**
```csharp
// Método sem retorno
void ExibirMensagem(string msg)

// Método com retorno
int Somar(int a, int b)

// Sobrecarga de método
double Calcular(double x, double y)
int Calcular(int x, int y)
```

---

### 🎓 **4. PClasses - Programação Orientada a Objetos**
**Funcionalidades:**
- Introdução a Classes e Objetos
- Propriedades e atributos
- Construtores
- Encapsulamento (public, private)
- Métodos da classe

**Conceitos aplicados:**
- Criação de classes
- Instanciação de objetos
- Modificadores de acesso
- Get e Set (propriedades)
- Construtores padrão e personalizados

**Exemplo de classe:**
```csharp
public class Pessoa
{
    // Atributos privados
    private string nome;
    private int idade;
    
    // Construtor
    public Pessoa(string nome, int idade)
    {
        this.nome = nome;
        this.idade = idade;
    }
    
    // Métodos
    public void Apresentar()
    {
        Console.WriteLine($"Olá, sou {nome} e tenho {idade} anos");
    }
}
```

---

### 📦 **5. Pvolume - Cálculo de Volume**
**Funcionalidades:**
- Calcula volume de diferentes sólidos geométricos
- Cubo, paralelepípedo, cilindro, esfera
- Fórmulas matemáticas precisas
- Menu de seleção interativo

**Conceitos aplicados:**
- Uso de Math.PI e Math.Pow
- Métodos com múltiplos parâmetros
- Formatação de saída numérica
- Constantes matemáticas

**Fórmulas implementadas:**
```
Cubo: V = lado³
Paralelepípedo: V = comprimento × largura × altura
Cilindro: V = π × raio² × altura
Esfera: V = (4/3) × π × raio³
```

**Exemplo de saída:**
```
Escolha o sólido:
1. Cubo
2. Paralelepípedo
3. Cilindro
4. Esfera

> 4
Digite o raio da esfera: 5
Volume da esfera: 523.60 cm³
```

---

## 🚀 Como Abrir e Executar

### **Pré-requisitos:**
- [Visual Studio 2019/2022](https://visualstudio.microsoft.com/pt-br/downloads/) instalado
- Workload: **.NET desktop development**

### **Executar um projeto:**

**Opção 1 - Visual Studio (Recomendado):**
1. Descompacte o arquivo `.zip` do projeto
2. Abra o arquivo `.sln` (Solution) no Visual Studio
3. Pressione `F5` ou clique no botão "▶ Iniciar"
4. O console será aberto automaticamente

**Opção 2 - Visual Studio Code:**
1. Abra a pasta do projeto no VS Code
2. Abra o terminal integrado
3. Execute:
```bash
dotnet run
```

**Opção 3 - Linha de Comando:**
```bash
# Navegar até a pasta do projeto
cd Pcalc

# Compilar e executar
dotnet build
dotnet run
```

---

## 🧠 Conceitos de C# Abordados

### **Fundamentos:**
- ✅ Tipos de dados primitivos (int, double, string, bool)
- ✅ Variáveis e constantes
- ✅ Operadores aritméticos, lógicos e relacionais
- ✅ Console.ReadLine() / Console.WriteLine()
- ✅ Conversões de tipo (Parse, Convert)

### **Estruturas de Controle:**
- ✅ if/else, switch-case
- ✅ for, while, do-while
- ✅ break, continue
- ✅ Estruturas aninhadas

### **Métodos e Funções:**
- ✅ Declaração e chamada de métodos
- ✅ Parâmetros e argumentos
- ✅ Tipos de retorno
- ✅ Sobrecarga de métodos (overload)
- ✅ Métodos estáticos

### **Orientação a Objetos (Introdução):**
- ✅ Classes e Objetos
- ✅ Atributos e Propriedades
- ✅ Construtores
- ✅ Encapsulamento (private, public)
- ✅ this keyword

### **Boas Práticas:**
- ✅ Nomenclatura PascalCase (métodos) e camelCase (variáveis)
- ✅ Comentários XML (///)
- ✅ Modularização de código
- ✅ Validação de entrada
- ✅ Tratamento de exceções

---

## 📊 Estatísticas do Repositório

- **Total de Projetos:** 5
- **Linguagem:** C# (.NET Framework / .NET Core)
- **IDE:** Visual Studio 2019/2022
- **Tipo:** Aplicações Console
- **Complexidade:** Básico a Intermediário
- **Linhas de Código:** ~400+

---

## 🎓 Disciplinas Relacionadas

Estes projetos foram desenvolvidos durante:

- **Linguagem de Programação II (LP2)** - Fatec
- **Algoritmos e Lógica de Programação**
- **Programação Orientada a Objetos**

---

## 🔧 Ambiente de Desenvolvimento

**IDE Principal:**
- Visual Studio 2022 Community Edition
- Visual Studio 2019 (compatível)

**Extensões úteis:**
- IntelliCode (sugestões de código)
- CodeMaid (organização de código)
- ReSharper (análise avançada - opcional)

**Frameworks:**
- .NET Framework 4.7+
- .NET Core 3.1 / .NET 5+ (alguns projetos)

---

## 📚 Recursos de Estudo

### **Documentação Oficial:**
- [Microsoft Learn - C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [Visual Studio Docs](https://docs.microsoft.com/pt-br/visualstudio/)
- [.NET Documentation](https://docs.microsoft.com/pt-br/dotnet/)

### **Tutoriais Recomendados:**
- [C# 101 - Microsoft Learn](https://channel9.msdn.com/Series/CSharp-101)
- [Curso C# - Gustavo Guanabara](https://www.youtube.com/playlist?list=PLHz_AreHm4dksSn0u_kMdz70sW4lUz25o)

### **Livros:**
- *"C# - Como Programar"* - Deitel & Deitel
- *"C# Essencial"* - Mark Michaelis

---

## 🐛 Melhorias Futuras

- [ ] Adicionar interface gráfica (Windows Forms)
- [ ] Implementar testes unitários
- [ ] Adicionar persistência em arquivos
- [ ] Criar validações mais robustas
- [ ] Documentação XML completa
- [ ] Refatorar usando SOLID principles

---

## 💡 Aprendizados

Durante o desenvolvimento destes projetos, aprendi:

1. **Sintaxe e estrutura do C#** - Base sólida na linguagem
2. **Visual Studio** - Domínio da IDE mais usada para C#
3. **Debug** - Uso de breakpoints e watch variables
4. **POO Básica** - Introdução a classes e objetos
5. **Métodos** - Modularização e reuso de código
6. **Matemática aplicada** - Fórmulas geométricas em código

---

## 📝 Observações Importantes

### **Estrutura dos projetos:**
Cada pasta contém:
- `Program.cs` - Arquivo principal com o método Main()
- Classes auxiliares (quando aplicável)
- `.csproj` - Arquivo de projeto do Visual Studio
- `.sln` - Solution file (abrir no VS)

### **Compatibilidade:**
- Projetos desenvolvidos em Visual Studio 2019/2022
- Compatíveis com .NET Framework 4.7+ e .NET Core 3.1+
- Podem ser abertos no Visual Studio Code (com .NET SDK)

---

## 🤝 Contribuindo

Este é um repositório de estudos pessoais da Fatec, mas sugestões de melhorias são bem-vindas!

Se tiver ideias ou encontrar bugs:
1. Abra uma [Issue](https://github.com/EduardoFProenca/CSharp-Console-Projects/issues)
2. Entre em contato

---

## 📈 Roadmap de Aprendizado

- [x] Sintaxe básica do C#
- [x] Estruturas de controle
- [x] Métodos e funções
- [x] Introdução a POO (Classes)
- [ ] POO avançada (Herança, Polimorfismo)
- [ ] Coleções e LINQ
- [ ] Windows Forms
- [ ] ASP.NET Core

---

## 👨‍💻 Autor

**Eduardo Ferreira Proença**

🎓 Estudante de Análise e Desenvolvimento de Sistemas - Fatec  
💼 Foco em Desenvolvimento Back-end  


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eduardo-ferreira-39106b26a)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EduardoFProenca)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eduardo.ferreira.proenca.brasil@gmail.com)

---

## 📄 Licença

Este projeto foi desenvolvido para fins **educacionais** durante o curso de ADS na Fatec.

---

## ⭐ Gostou?

Se este repositório te ajudou nos estudos, deixe uma ⭐!

---

<div align="center">

**Desenvolvido com 💙 no Visual Studio durante os estudos na Fatec**

*"Aprenda fazendo. A prática leva à perfeição."*

</div>
