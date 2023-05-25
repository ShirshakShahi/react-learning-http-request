# PUSH method in React :

```javascript
const addDataHandler=async(datas)=>{
    const response = await fetch('url',{
      method : 'POST',
      body : JSON.stringfy(datas),
      headers:{
        'content-type':'application/json'
      }
    })
    const data = await response.json();
}