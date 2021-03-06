# LitElement, Polymer v2 / v3, and Web Components  Snippets for Visual Studio Code

This extension for Visual Studio Code adds snippets for LitElement and Polymer v2/v3 for JavaScript and HTML.

[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/justinribeiro.Polymer2Snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=justinribeiro.Polymer2Snippets) [![Current Release](https://vsmarketplacebadge.apphb.com/version/justinribeiro.Polymer2Snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=justinribeiro.Polymer2Snippets)

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

### JavaScript Snippets
```javascript
p-polymer-element         // Polymer 3 Web Component definition
p-lit-element             // LitElement Web Component definition
p-hybridbehaviors         // Polymer.mixinBehaviors()
p-lifecycle-constructor   // constructor()
p-lifecycle-connected     // connectedCallback()
p-lifecycle-disconnected  // disconnectedCallback()
p-lifecycle-attrchanged   // attributeChangedCallback()
p-lifecycle-ready         // Polymer specific ready()
p-dispatchevent           // Fire custom event with this.dispatchEvent();
p-dispatchevent-composed  // Fire custom event through ShadowDOM
p-observers               // Polymer static get observers()
p-properties              // Polymer static get properties()
p-property-basic          // Polymer property w/type + default value
p-property-observer       // Polymer property w/type + default value + observer
p-property-computed       // Polymer property w/type + computed
p-property-all            // Polymer property with everything
p-mixin                   // ES6 arrow function subclass return
p-mixin-dedup             // Sharable mixin utilizing Polymer's dedupingMixin
l-element                 // LitElement Web Component definition (alias p-lit-element)
l-render-html             // LitElement render() with html``
l-render-svg              // LitElement render() with svg``
l-firstRendered           // LitElement firstRender()
l-properties              // Lit-Element properties by implementing a static properties getter
l-get-styles              // Lit-Element styles in a static styles property
l-get-styles-super        // Lit-Element static styles property with super class
l-firstUpdated            // Lit-Element firstUpdated()
l-shouldUpdate            // Lit-Element shouldUpdate()
l-requestUpdate           // Lit-Element requestUpdate()
l-updateComplete          // Lit-Element `await this.updateComplete;`
```

### HTML Snippets
```html
p-webcomponent            // Boilerplate Polymer 2 Web Component
p-mixin                   // Boilerplate Polymer 2 mixin class
p-mixin-dedup             // Boilerplate Polymer 2 mixin class utilizing Polymer.dedupingMixin()
p-slot                    // <slot name="">
p-dom-repeat-inside       // dom-repeat inside Polymer managed template
p-dom-if                  // dom-if
```

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Installation

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code
