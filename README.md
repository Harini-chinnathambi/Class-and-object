# Class-and-object
void display() {
            System.out.println("Name: " + name);
            System.out.println("Age: " + age);
        }
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        ClassObject obj = new ClassObject();
        Student s1 = obj.new Student();
        System.out.print("Enter the student's name:");
        s1.name = sc.nextLine();

        System.out.print("Enter the student's age:");
        s1.age = sc.nextInt();

       
        System.out.println("\nStudent Details:");
        s1.display();

        sc.close();
    }
}
Output 
Enter the student's name:harini
Enter the student's age:18

Student Details:
Name: harini
Age: 18
