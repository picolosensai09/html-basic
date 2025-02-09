# html-basic
basic uses of  tags
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Basic Idea</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
    <style></style>
   
</head>
<body>
    <!-- 6 Headings Tags -->
    <h1 style="color: red;">Welcome To My Page</h1>
    <h2 style="color: rgb(30, 94, 151);">Welcome To My Page</h2>
    <h3 style="color: aqua;">Welcome To My Page</h3>
    <h4 style="color: rgb(22, 151, 151);">Welcome To My Page</h4>
    <h5 style="color: blue;">Welcome To My Page</h5>
    <h6 style="color: yellow;">Welcome To My Page</h6>
    <h7 style="color: green;">Welcome To My Page</h7>

<!-- <p> tag is used to insert the pparagraph -->

    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo, possimus provident. Eum magni distinctio saepe a voluptate dolorem perspiciatis, laboriosam fugit tempora maxime deleniti eligendi nihil, placeat autem! Nemo, sapiente.
    </p><br><hr>
    <p>
        HTML (HyperText Markup Language) is the standard language used to create and structure web pages. It provides the basic framework for web content by using a system of elements and tags that define headings, paragraphs, links, images, lists, and other elements of a webpage.
    </p><br><hr>

<!-- <b> tag is used to bold text -->

    <b>
        A computer is an electronic device that processes data and performs various tasks based on user instructions. It can store, retrieve, and manipulate information quickly and efficiently.
    </b><br><hr>

<!-- strong tag is used to bold the text -->

   <strong>
    Computers come in different forms, including desktops, laptops, tablets, and even smartphones. They are used in almost every field, from education and business to healthcare and entertainment.
   </strong><br><hr>

<!-- <i> tag is used to underline the text -->

    <i>
        The central processing unit (CPU) is the brain of the computer. It performs calculations and executes instructions given by software programs.

    </i><br><hr>

<!-- <u> tag is use to underline the text -->

    <u>
        Computers use hardware (physical components) and software (programs and operating systems) to function. Both work together to complete various tasks.

    </u><br><hr>

<!-- <mark> tag is use to highlight the text -->

    <mark>
        A programming language is a way for humans to communicate with computers. It consists of a set of instructions that a computer can understand and execute.

    </mark><br><hr>

<!-- <del> tag is used to cut the text with underline -->

    <del>
        There are many programming languages, such as Python, Java, C++, and JavaScript. Each has its own purpose and is used for different types of applications.

    </del><hr><br>

<!-- <smaall> tag is used to -->

    <small>
        Programming languages are classified into high-level and low-level languages. High-level languages are user-friendly, while low-level languages are closer to machine code.

    </small><hr><br>

<!-- <su> tag is used to get text in above the normal line -->

    <sup>
        Learning to code helps people develop problem-solving skills and logical thinking. It is a valuable skill in today’s technology-driven world.

    </sup><hr><br>
    
<!-- <sub> tag is used to get text in below the normal line -->

    <sub>
        Many industries rely on programming to develop websites, mobile apps, software, and artificial intelligence systems. It is an essential part of modern innovation.

    </sub><hr><br>

    <!-- <pre> its use to displays the text exactly as it was written -->

    <pre>
        import java.util.Scanner;

public class SimpleCalculator {
    public static void main(String[] args) {
        // Create Scanner object for user input
        Scanner scanner = new Scanner(System.in);

        // Ask the user for two numbers
        System.out.print("Enter first number: ");
        double num1 = scanner.nextDouble();

        System.out.print("Enter second number: ");
        double num2 = scanner.nextDouble();

        // Ask the user for an operation
        System.out.print("Enter operation (+, -, *, /): ");
        char operation = scanner.next().charAt(0);

        double result = 0;

        // Perform the calculation based on the operation
        switch (operation) {
            case '+':
                result = num1 + num2;
                break;
            case '-':
                result = num1 - num2;
                break;
            case '*':
                result = num1 * num2;
                break;
            case '/':
                if (num2 != 0) {
                    result = num1 / num2;
                } else {
                    System.out.println("Error: Division by zero is not allowed.");
                    return;
                }
                break;
            default:
                System.out.println("Invalid operation. Please enter +, -, *, or /.");
                return;
        }

        // Display the result
        System.out.println("Result: " + result);

        // Close the scanner
        scanner.close();
    }
}

    </pre>
</body>
</html>
