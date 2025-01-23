# Constructor
class Student {
    String name;
    int age;
    String grade;
    Student(String name, int age, String grade) {
        this.name = name;
        this.age = age;
        this.grade = grade;
    }
    void displayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Grade: " + grade);
    }
}
public class ConstructorExample {
    public static void main(String[] args) {
        Student student1 = new Student("Alice", 20, "A");
        Student student2 = new Student("Bob", 22, "B");
        System.out.println("Student 1 Details:");
        student1.displayDetails();
        System.out.println("\nStudent 2 Details:");
        student2.displayDetails();
    }
}
Output 
Student 1 Details:
Name: Alice
Age: 20
Grade: A

Student 2 Details:
Name: Bob
Age: 22
Grade: B
