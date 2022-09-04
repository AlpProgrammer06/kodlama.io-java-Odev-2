```
package com.company;

public class InstructorManeger extends UserManeger {
    @Override
    public void login(User user) {

        System.out.println(user.getName() + " Egitmen girisi yapildi ");
    }

    public void addLesson(User user) {
        System.out.println(" Ders eklendi. ");
    }

    public void addLesson() {
    }
}

```