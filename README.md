# pd-playground

### Install

```
npm i pd-playground
```

### Useage

```javascript
import React from "react";
import { EditorProvider, Playground } from "pd-playground";

const App = () => {
  // initial code
  const initialCode = 'dd = {content: "Hello "}';

  // code state
  const [code, setCode] = React.useState(initialCode);

  return (
    <EditorProvider code={code} setCode={setCode}>
      <Playground />
    </EditorProvider>
  );
};

export default App;
```

### Version

### Local development

pull the repository to local
cd to 'pd-playground' folder

```
sudo npm link
sudo npm link  'test react folder'/node_modules/react
```

Then go to Test folder

```
npm link pd-Playground
```

When you finish test remember to unlink by use

```
npm unlink pd-playground
```
