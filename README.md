# Template Newsletter HTML

Um template responsivo e compatível com clientes de email para criação de newsletters profissionais.

## Características

### ✨ Recursos Principais
- **Responsivo**: Adapta-se automaticamente a diferentes tamanhos de tela
- **Dark Mode**: Suporte nativo ao modo escuro com `prefers-color-scheme`
- **Compatibilidade**: Otimizado para Outlook (MSO) e outros clientes de email
- **Design Moderno**: Layout limpo e profissional

### 🎨 Elementos de Design
- Botões estilizados com hover effects
- Tipografia Arial para máxima compatibilidade
- Esquema de cores laranja/amarelo
- Largura máxima de 700px para melhor legibilidade

### 📱 Responsividade
- Breakpoint em 600px para dispositivos móveis
- Ajustes automáticos de padding e largura
- Imagens responsivas com `max-width: 100%`

## Estrutura do Template

```
├── Header (vazio - pronto para personalização)
├── Content (área principal do conteúdo)
├── Footer (vazio - pronto para personalização)
└── Texto de cancelamento de inscrição
```

## Como Usar

1. **Adicionar Conteúdo**: Insira seu HTML na seção marcada com o comentário:
   ```html
   <!-- Cole aqui o html que contém o conteudo -->
   ```

2. **Imagens**: Ao adicionar imagens, use sempre:
   ```html
   <img src="..." style="max-width:100%;height:auto;display:block;margin:0;">
   ```

3. **Personalizar Cores**: Modifique as variáveis CSS nas linhas 87-104 para ajustar a paleta de cores.

## Compatibilidade

- ✅ Outlook (todas as versões)
- ✅ Gmail
- ✅ Apple Mail
- ✅ Thunderbird
- ✅ Clientes web e mobile

## Suporte a Dark Mode

O template detecta automaticamente a preferência do usuário e ajusta:
- Cores de texto para branco
- Background escuro (#333)
- Imagens específicas para modo escuro (classe `.dark-img`)

## Notas Técnicas

- Usa tabelas para máxima compatibilidade com clientes de email
- Inclui fallbacks para Outlook com comentários condicionais `<!--[if mso]-->`
- Meta tags otimizadas para renderização em diferentes dispositivos