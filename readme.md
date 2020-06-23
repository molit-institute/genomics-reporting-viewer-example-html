# Stencil Components Example HTML

This is an example Project showcasing the useage of stencil-components in an HTML-Project.

## Using the components

### Script tag

- Put the following script tag in the head of your index.html

```html
<script src="https://unpkg.com/stencil-components/latest/dist/stencil-components.js></script>
```

or

- If Edge or IE11 are targeted use the following script 

```html
<script type="module"> 
    import { applyPolyfills, defineCustomElements } from 'https://unpkg.com/stencil-components/loader'; 
        applyPolyfills().then(() => {
        defineCustomElements();
    });
</script>
```
- Then you can use the element anywhere in your template, JSX, html etc

### Node Modules
- Run `npm install stencil-components --save`
- Put a script tag similar to this `<script src="/node_modules/stencil-components/dist/stencil-components.js"></script>` in the head of your index.html
- Then you can use the element anywhere in your template, JSX, html etc
