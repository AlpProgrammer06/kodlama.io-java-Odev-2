```
package com.company;

public class User {
    private int id;
    private String name;

    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }





}
package com.company;

public class UserManeger {

    public void login(User user) {
        System.out.println(user.getId()+" giris yapildi ");
    }

   public void logins(User[] users){
        for(User user : users){
            login(user);
        }
   }


}

```