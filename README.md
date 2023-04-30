import java.util.Scanner;

public class Test {
    public static void main(String[] args) throws RuntimeException {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Введите числа римские или арабские от 1 до 10 в формате:\nчисло1 пробел оперант пробел число2: ");
        String str1 = scanner.nextLine();
        String[] strings = str1.split(" ");
        int size = strings.length;


