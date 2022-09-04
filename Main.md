```
package com.company;

public class Main {

    public static void main(String[] args) {
        Instructor instructor=new Instructor();
        instructor.setId(1);
        instructor.setName(" Engin Demirog ");
        instructor.setBranch(" java ");

        InstructorManeger instructorManeger=new InstructorManeger();
        instructorManeger.addLesson();
        instructorManeger.login(instructor);

        Student student=new Student();
        student.setId(2);
        student.setName("Aslan Balci");
        student.setEmail("aslanbalci05@gmail.com");

        StudentManeger studentManeger=new StudentManeger();
        studentManeger.login(student);
        studentManeger.chooseCourse();

        UserManeger userManeger=new UserManeger();
        User[] users={instructor,student};
        userManeger.logins(users);


    }
}
```