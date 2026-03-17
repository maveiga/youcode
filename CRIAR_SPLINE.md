# 🎨 Como Criar Spline Branco & Azul

## Passo a Passo (5 minutos)

### 1. Acesse o Spline
- Vá em: **https://spline.design/**
- Clique em **"Get Started"** → **"New File"**

### 2. Crie a cena básica
1. Delete os objetos padrão (selecione e pressione Delete)
2. No menu esquerdo, clique em **"+" → "Cube"** ou **"Sphere"**
3. Adicione 2-3 formas geométricas

### 3. Aplique as cores do seu site
Para cada objeto:
1. Selecione o objeto
2. No painel direito, vá em **"Materials"**
3. Clique em **"Color"**
4. Use estas cores:

| Elemento | Cor Hex | Uso |
|----------|---------|-----|
| Branco Principal | `#FFFFFF` | Formas principais |
| Azul Primário | `#1a56db` | Detalhes |
| Azul Claro | `#3b73f0` | Gradientes |
| Azul Suave | `#60a5fa` | Reflexos |

### 4. Configure o Material
- **Type**: Standard ou Physical
- **Color**: Escolha uma das cores acima
- **Roughness**: 0.3 (para brilho suave)
- **Metalness**: 0.1

### 5. Adicione Animação (opcional)
1. Selecione um objeto
2. Clique em **"Animation"** no topo
3. Escolha **"Rotate"** ou **"Float"**
4. Ajuste velocidade: 2-3 segundos

### 6. Exporte
1. Clique em **"Export"** (canto superior direito)
2. Escolha **"Viewer"** ou **"SplineCode"**
3. Copie a URL gerada (ex: `https://prod.spline.design/SEU_CODIGO/scene.splinecode`)

### 7. Atualize seu index.html
```html
<spline-viewer url="SUA_NOVA_URL_AQUI"></spline-viewer>
```

---

## 🎯 Cores Exatas do Seu Site

```css
--primary:      #1a56db  /* Azul principal */
--primary-lt:   #3b73f0  /* Azul claro */
--bg:           #ffffff  /* Branco */
--bg-2:         #f4f6f9  /* Branco gelo */
```

---

## 💡 Dica Rápida

Se quiser algo **imediatamente**, use esta cena pública de exemplo:
- Substitua no seu HTML e depois customize no Spline

URL temporária para testes:
```
https://prod.spline.design/kZDDjO5HuC9GJUM2/scene.splinecode
```
(Edite esta cena no Spline e salve como cópia sua)

---

## 🔗 Links Úteis

- **Spline Editor**: https://spline.design/
- **Tutorial Iniciante**: https://spline.design/tutorials
- **Comunidade**: https://discord.gg/spline
