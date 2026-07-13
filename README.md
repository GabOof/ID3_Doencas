# ID3 Doenças - Sistema de Diagnóstico Médico

## 📋 Descrição

Sistema web inteligente para apoio a diagnósticos médicos baseado em **Árvore de Decisão** utilizando o algoritmo **ID3** (Iterative Dichotomiser 3). O sistema analisa sintomas e características clínicas para auxiliar no processo diagnóstico.

## 🎯 Objetivos

- Fornecer uma ferramenta de apoio ao diagnóstico médico
- Utilizar inteligência artificial (algoritmo ID3) para análise de sintomas
- Oferecer interface amigável e intuitiva para usuários
- Armazenar e processar dados clínicos de forma estruturada

## 🛠️ Tecnologias Utilizadas

- **JavaScript** (44.7%) - Lógica frontend e interatividade
- **Python** (17.3%) - Backend e processamento de dados/algoritmo ID3
- **HTML** (16.7%) - Estrutura das páginas
- **CSS** (21.3%) - Estilização e design responsivo

## 🚀 Funcionalidades

- ✅ Interface web responsiva para input de sintomas
- ✅ Algoritmo ID3 para construção e navegação em árvore de decisão
- ✅ Análise de padrões clínicos
- ✅ Sugestão de diagnósticos baseada em dados
- ✅ Sistema interativo de perguntas diagnósticas

## 📁 Estrutura do Projeto

```
ID3_Doencas/
├── frontend/          # Arquivos HTML, CSS e JavaScript
├── backend/           # Scripts Python e lógica do algoritmo
├── data/              # Dados clínicos e conjuntos de treino
└── README.md          # Este arquivo
```

## ⚙️ Instalação

### Requisitos
- Python 3.6+
- Node.js (opcional, para ferramentas frontend)
- Navegador web moderno

### Passos

1. **Clone o repositório**
   ```bash
   git clone https://github.com/GabOof/ID3_Doencas.git
   cd ID3_Doencas
   ```

2. **Instale as dependências Python**
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute o servidor**
   ```bash
   python app.py
   ```

4. **Acesse no navegador**
   ```
   http://localhost:5000
   ```

## 📖 Como Usar

1. Acesse a interface web do sistema
2. Responda às perguntas sobre os sintomas do paciente
3. O algoritmo ID3 processará as respostas e navegará pela árvore de decisão
4. Receba sugestão de possível diagnóstico
5. **Importante**: Use como ferramenta de apoio apenas, não substitui avaliação médica profissional

## 🧠 Sobre o Algoritmo ID3

O algoritmo ID3 é um algoritmo de aprendizagem de máquina que constrói árvores de decisão através de:
- Seleção de atributos baseada em ganho de informação
- Recursão para construir subárvores
- Classificação de dados em categorias (neste caso, doenças)

## ⚠️ Aviso Legal

Este sistema é uma **ferramenta educacional e de apoio** e não deve ser utilizado como substituto para diagnóstico médico profissional. Sempre consulte um médico qualificado para qualquer preocupação de saúde.

## 👤 Autor

**GabOof**

## 📝 Licença

Este projeto está disponível sob licença a ser definida. Verifique o arquivo `LICENSE` para mais informações.

## 🤝 Contribuições

Contribuições são bem-vindas! Para reportar bugs ou sugerir melhorias:

1. Abra uma issue descrevendo o problema/sugestão
2. Faça um fork do repositório
3. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
4. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
5. Push para a branch (`git push origin feature/AmazingFeature`)
6. Abra um Pull Request

## 📞 Contato

Para dúvidas ou sugestões, abra uma issue neste repositório.

---

**Desenvolvido com ❤️ para fins educacionais e de pesquisa**
