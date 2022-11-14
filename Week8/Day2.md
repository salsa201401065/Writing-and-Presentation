# Writing-and-Presentation Week8
## **React Context**
- Menghindari props drilling (Mempassing props dari grandparent ke parent ke child ke grandchild dan seterusnya)

## **Create React Context**
- Import createContext 
```html
import { createContext } from 'react';

export const LevelContext = createContext(1);
```
## **Implementasi React Context**
```html
import React, { useState, useContext } from "react";
  
let context = React.createContext(null);
function Parent() {
  const [fName, setfName] = useState("firstName");
  const [lName, setlName] = useState("LastName");
  return (
    <context.Provider value={{ fName, lName }}>
      <div>This is a Parent component</div>
      <br />
      <ChildA />
    </context.Provider>
  );
}
  
function ChildA() {
  return (
    <>
      This is ChildA Component.
      <br />
      <ChildB />
    </>
  );
}
  
function ChildB() {
  return (
    <>
      This is ChildB Component.
      <br />
      <ChildC />
    </>
  );
}
  
function ChildC() {
  const { fName, lName } = useContext(context);
  return (
    <>
      This is ChildC component.
      <br />
      <h3> Data from Parent component is as follows:</h3>
      <h4>{fName}</h4>
      <h4>{lName}</h4>
    </>
  );
}
  
export default Parent;
```

Output :

![Screenshot (250)](https://user-images.githubusercontent.com/85721113/201662513-10c6542c-7929-4ebb-be28-e2aa0c07b27e.png)

