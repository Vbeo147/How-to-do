# How-to-do

<details>
<summary>React</summary>
  <ul>
  <li>
    <h1>How to change React Element to HTMLElement</h1>

        const ReactElement = <div>Hello World</div>
        const root = document.createElement("div") or document.createDocumentFragment();
        
        root.id = "root";
        
        const newRoot = createRoot(root);
        newRoot.render(ReactElement);
        
        console.log(root);
        // it wil return that rendered HTMLElement.
        // it cannot get childNodes. i dont know why this.
        // it can insert to any HTMLElement.
        
  </li>
  </ul>
</details>
