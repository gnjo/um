# um
um is unitymacro

```c#
 
 //usage
  async Task Start(){
    //var data =new Dictonary<string,object>();
    var gd = gameobject.root.GetObject("GAMEDATA").GetComponent<GameData>();
    var data =gd.vals;
    var um = new UM();
    await um.Run(script,ref data);
    Debug.Log("end");
  }
 
 
 
 //define 
 public class UM{
  
  public async Task Run(string text,ref Dictronary<string,object> dic){
  
  }
  
 
 }
 
```


