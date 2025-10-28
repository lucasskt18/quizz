# 📖 Quiz: Mulheres na Bíblia

## 📝 Descrição

Quiz interativo sobre as importantes mulheres que marcaram a história bíblica. Aplicação web local projetada para rodar em totens sem acesso à internet. O software funciona perfeitamente offline e foi otimizado para exibição em telas de TV via HDMI.

## ✨ Características

- ✅ **100% Offline** - Funciona sem internet
- ✅ **Interface Moderna** - Design responsivo e profissional
- ✅ **Fácil Configuração** - Apenas edite o arquivo HTML
- ✅ **Armazenamento Local** - Salva resultados automaticamente
- ✅ **Responsivo** - Adapta-se a diferentes tamanhos de tela
- ✅ **Visual Atrativo** - Gradientes e animações suaves

## 🚀 Como Usar

### 1. Instalação no Totem

1. **Copie o arquivo `quiz.html` para um pen drive**
2. **No dia do evento**: 
   - Conecte o notebook à TV via cabo HDMI
   - Plugue o pen drive no notebook
   - Abra o arquivo `quiz.html` no navegador
   - Ajuste para tela cheia (F11 no navegador)

### 2. Perguntas do Quiz

Este quiz contém **10 perguntas** sobre mulheres importantes da Bíblia:

1. **Eva** - A primeira mulher criada
2. **Maria** - Mãe de Jesus
3. **Ester** - Rainha que salvou o povo judeu
4. **Esposa de Ló** - Transformada em estátua de sal
5. **Noemi** - Sogra de Rute
6. **Débora** - Juíza e profetisa
7. **Raabe** - Ajudou os espias em Jericó
8. **Rute** - Conhecida por sua fidelidade
9. **Miriã** - Irmã de Moisés
10. **Dalila** - Distraiu Sansão

### 3. Editar as Perguntas (Opcional)

Se desejar personalizar, abra o arquivo `quiz.html` e procure pela seção:

```javascript
// PERGUNTAS DO QUIZ - Mulheres na Bíblia
const questions = [
    {
        question: "Sua pergunta aqui?",
        options: ["Opção A", "Opção B", "Opção C", "Opção D"],
        correct: 0  // Índice da resposta correta (0=A, 1=B, 2=C, 3=D)
    },
    // ... adicione mais perguntas
];
```

### Exemplo de Como Adicionar Perguntas:

```javascript
{
    question: "Qual é a maior cidade do Brasil?",
    options: ["São Paulo", "Rio de Janeiro", "Brasília", "Salvador"],
    correct: 0  // São Paulo é a resposta correta
}
```

**Importante:**
- O campo `correct` usa índice (0 para primeira opção, 1 para segunda, etc.)
- Mantenha sempre 4 opções por pergunta
- O total recomendado é de 10 perguntas (podendo ter mais ou menos)

## 📊 Funcionalidades

### Tela de Início
- Apresenta o quiz ao usuário
- Botão para iniciar

### Durante o Quiz
- **Barra de progresso** no topo
- **Numeração** da pergunta atual
- **Hover effects** nas opções
- **Botão anterior/próxima** para navegação

### Tela de Resultado
- Exibe o score final (ex: 7/10)
- Mostra porcentagem de acertos
- Mensagem personalizada conforme desempenho
- Botão para refazer o quiz
- Salva resultado no histórico local

### Armazenamento
- Os resultados são salvos automaticamente no navegador
- Acesse via DevTools > Application > Local Storage
- Limite de 100 resultados anteriores

## 🎨 Personalização (Opcional)

Você pode personalizar as cores editando as seções CSS no arquivo:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Cores atuais:
- **Primária**: #667eea (azul roxo)
- **Secundária**: #764ba2 (roxo)

## 🖥️ Requisitos do Sistema

- **Navegador**: Chrome, Firefox, Edge, ou Safari
- **Sistema**: Windows, macOS, ou Linux
- **Internet**: Não necessária (roda 100% offline)

## 💡 Dicas de Uso

1. **Modo Tela Cheia**: Pressione F11 no navegador para modo fullscreen
2. **Teste Antes**: Sempre teste o quiz antes do evento
3. **Responsividade**: Funciona bem em TVs de 32" até 65"
4. **Backup**: Mantenha uma cópia extra do arquivo
5. **Navegação**: Use mouse touchpad ou controle USB

## 🔧 Solução de Problemas

### Quiz não abre?
- Verifique se o arquivo está em `.html` (não `.html.txt`)
- Abra com um navegador moderno (Chrome recomendado)

### Perguntas não aparecem?
- Verifique a sintaxe JavaScript no arquivo
- Certifique-se de que todas as perguntas têm 4 opções

### Interface não responsiva?
- Ajuste a resolução da TV para Full HD (1920x1080)
- Use modo tela cheia

## 📱 Suporte

Este é um arquivo único (HTML standalone) que contém:
- ✅ HTML (estrutura)
- ✅ CSS (estilização)
- ✅ JavaScript (funcionalidade)

Tudo em um único arquivo para máxima portabilidade!

## 📝 Licença

Uso livre para eventos e projetos educacionais.

---

**Versão:** 1.0  
**Data:** 2024  
**Compatibilidade:** Todos os navegadores modernos

