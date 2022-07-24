# Neon Lights
<p align="justify">Neon Lights é uma biblioteca que inclui cores brilhantes no estilo neon, juntamente com suas animações.</p>

## Importação
<p>Faça o download do arquivo "neon.css", encontrado neste repositório, e coloque-o em seu projeto.</p>

```html
<link rel="stylesheet" href="path/to/neon.css">
```

## Docs

### Texto
* Texto estático: 
    ```html 
    <p class="neon-text" style="--color: #00ffff">Hello</p>
    ```
* Texto animado: 
    ```html 
    <p class="neon-text-pulse" style="--color: #00ffff; --time: 2.0s">Hello</p>
    ```

### Caixa
* Caixa estática: 
    ```html 
    <p class="neon-box" style="--color: #00ffff">Hello</p>
    ```
* Caixa animada: 
    ```html 
    <p class="neon-box-pulse" style="--color: #00ffff; --time: 1.5s">Hello</p>
    ```

### Variáveis
* Color: 
    ```html 
    <p class="neon-box" style="--color: #00ffff">Hello</p>
    ```
    <p> "--color" representa a cor de um texto (para neon-text) ou a cor de fundo (para neon-box). O valor deve  ser passado no atributo "style", embutido na tag HTML. Ao utilizar as classes "neon", é  necessário atribuir um valor para "--color"
    </p>
    
* Time: 
    ```html 
    <p class="neon-text-pulse" style="--color: #00ffff; --time: 0.5s">Hello</p>
    ```
    <p> "--time" representa o tempo de duração de uma animação. O valor deve ser passado no atributo "style", embutido na tag HTML. Ao utilizar as classes "neon" que possuem animação, é necessário atribuir um valor para "--time", no formato "2.0s".
    </p>
    
### Animações
* Pulse
  ```html 
  <p class="neon-text-pulse" style="--color: #00ffff; --time: 4.0s">Hello</p>
  ```
  
  ```html 
  <p class="neon-box-pulse" style="--color: #00ffff; --time: 2.5s">Hello</p>
  ```
  
## Próximos passos
* Estilos para React
* Estilos para React-Native
* Novas animações
  


