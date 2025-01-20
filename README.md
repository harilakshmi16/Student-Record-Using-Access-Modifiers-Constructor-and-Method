# Student-Record-Using-Access-Modifiers-Constructor-and-Method
Student Record Using Access Modifiers, Constructor, and Method

class StudentRecord {
    private String name;
    private int age;

    public StudentRecord(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public void displayRecord() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}

public class StudentRecordExample {
    public static void main(String[] args) {
        StudentRecord student = new StudentRecord("Emma", 20);
        student.displayRecord();
    }
}

Output

Name: Emma  
Age: 20
