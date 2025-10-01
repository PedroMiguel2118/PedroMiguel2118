# 💻 Desenvolvedor Full Stack - Python, JavaScript, HTML & CSS

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

🚀 **Desenvolvimento Web Full Stack**

</div>

## 🛠️ Minhas Tecnologias

<div align="center">

### 🐍 Python
![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-Intermediate-000000?style=flat-square&logo=flask)
![Django](https://img.shields.io/badge/Django-Intermediate-092E20?style=flat-square&logo=django)

### 🌐 Frontend
![HTML5](https://img.shields.io/badge/HTML5-Expert-E34F26?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Expert-1572B6?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Advanced-F7DF1E?style=flat-square&logo=javascript)

</div>

## 💡 Habilidades Técnicas

### 🐍 Python
```python
class HabilidadesPython:
    def __init__(self):
        self.conhecimentos = [
            "Programação Orientada a Objetos",
            "APIs REST com Flask/FastAPI",
            "Automação de tarefas",
            "Web Scraping com BeautifulSoup",
            "Processamento de dados",
            "Scripts para backend"
        ]
    
    def mostrar_projetos(self):
        projetos = {
            "web_apps": "Aplicações web completas",
            "apis_rest": "APIs robustas e escaláveis",
            "automacao": "Scripts de automação",
            "data_processing": "Processamento de dados"
        }
        return projetos

dev = HabilidadesPython()
print("🚀 Projetos Python:", dev.mostrar_projetos())

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Dinâmico</title>
    <style>
        :root {
            --primary: #667eea;
            --secondary: #764ba2;
            --accent: #f093fb;
            --text: #2d3748;
            --light: #f7fafc;
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            padding: 2rem;
        }
        
        .skill-card {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            padding: 2rem;
            border-radius: 15px;
            color: white;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }
        
        .skill-card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            transform: rotate(45deg);
            transition: all 0.6s ease;
        }
        
        .skill-card:hover::before {
            transform: rotate(45deg) translate(50%, 50%);
        }
        
        .skill-card:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }
        
        .python-card {
            background: linear-gradient(135deg, #3776AB, #306998);
        }
        
        .js-card {
            background: linear-gradient(135deg, #F7DF1E, #D4BB00);
            color: #2d3748;
        }
        
        .html-card {
            background: linear-gradient(135deg, #E34F26, #C53707);
        }
        
        .css-card {
            background: linear-gradient(135deg, #1572B6, #0D5A9D);
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
        }
        
        .floating {
            animation: float 4s ease-in-out infinite;
        }
        
        .pulse {
            animation: pulse 2s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
    </style>
</head>
<body>
    <div class="skills-container">
        <div class="skill-card python-card floating">
            <h3>🐍 Python</h3>
            <p>Backend robusto • APIs • Automação</p>
            <div class="skill-bar">
                <div class="bar" style="width: 90%;"></div>
            </div>
        </div>
        
        <div class="skill-card js-card pulse">
            <h3>⚡ JavaScript</h3>
            <p>Interatividade • Dinamismo • Lógica</p>
            <div class="skill-bar">
                <div class="bar" style="width: 85%;"></div>
            </div>
        </div>
        
        <div class="skill-card html-card">
            <h3>🛠️ HTML5</h3>
            <p>Estrutura • Semântica • Acessibilidade</p>
            <div class="skill-bar">
                <div class="bar" style="width: 95%;"></div>
            </div>
        </div>
        
        <div class="skill-card css-card floating">
            <h3>🎨 CSS3</h3>
            <p>Design • Animações • Responsividade</p>
            <div class="skill-bar">
                <div class="bar" style="width: 92%;"></div>
            </div>
        </div>
    </div>

    <script>
        // Interatividade com JavaScript
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.skill-card');
            
            cards.forEach(card => {
                card.addEventListener('mouseenter', function() {
                    this.style.transform = 'translateY(-15px) scale(1.08)';
                });
                
                card.addEventListener('mouseleave', function() {
                    this.style.transform = 'translateY(0px) scale(1)';
                });
            });
            
            // Efeito de digitação dinâmico
            const texts = ['Python Developer', 'JavaScript Expert', 'Frontend Specialist', 'Full Stack Developer'];
            let count = 0;
            let index = 0;
            let currentText = '';
            let letter = '';
            
            function typeWriter() {
                if (count === texts.length) {
                    count = 0;
                }
                currentText = texts[count];
                letter = currentText.slice(0, ++index);
                
                const typingElement = document.createElement('div');
                typingElement.className = 'typing-effect';
                typingElement.style.cssText = `
                    text-align: center;
                    font-size: 1.5rem;
                    font-weight: bold;
                    margin: 2rem 0;
                    color: #667eea;
                    min-height: 2rem;
                `;
                
                if (!document.querySelector('.typing-effect')) {
                    document.body.appendChild(typingElement);
                }
                
                document.querySelector('.typing-effect').textContent = letter;
                
                if (letter.length === currentText.length) {
                    setTimeout(() => {
                        count++;
                        index = 0;
                        typeWriter();
                    }, 2000);
                } else {
                    setTimeout(typeWriter, 100);
                }
            }
            
            typeWriter();
        });
    </script>
</body>
</html>
