```

}package com.company;

public class StudentManeger extends UserManeger{
    @Override
    public void login(User user){
        System.out.println(user.getName()+ " Ogrenci girisi yapildi ");
    }
    public void chooseCourse(){
        System.out.println(" kurs secildi. ");
    }
}

```