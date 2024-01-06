# homework
переробив
1
public class Main {
public static void main(String[] args) {
String[] Seasons = {"Зима", "Весна", "Лето", "Осень", "Что-то еще", "Лето"};
String targetWord = "Лето";

    int index = -1;
    
    for(int i = 0; i < seasons.length; i++) {
        if(seasons[i].equals(targetWord)) {
            index = i;
            break;
        }
    }
    
    System.out.println("Елемент \"" + targetWord + "\" має індекс " + index);
}
}
2
public class Main {
public static void main(String[] args) {
char[] chars = {'A', 'b', 'C', 'D', 'e', ​​'F', '1' , '#'};

    char target = 'C';
    int index = -1;

    for (int i = 0; i < chars.length; i++) {
        if (chars[i] == target) {
            index = i;
            break;
        }
    }

    System.out.println("Елемент масива з індексом " + index + " -> '" + target + "'");
    System.out.println("Елемент '" + target + "' має індекс " + index);
}
}
3
int[] ints = {10, 21, 7, 98, 99, 4, 3, 4, 9};
int searchDigit = 7;

for (int i = 0; i < ints.length; i++) {
if (ints[i] == searchDigit) {
System.out.println("Елемент " + searchDigit + " має індекс " + i);
перерыв;
}
}
4
общественный класс Main {
public static void main(String[] args) {
int[] array = new int[10];

    for (int i = 0; i < array.length; i++) {
        array[i] = i + 1;
    }

    for (int i = 0; i < array.length; i++) {
        System.out.print(array[i] + " ");
    }
}
}
5
String[]words = {"яблоко", "банан", "вишня", "яблоко", "банан", "грейпфрут"};
Строка LastWord = слова[words.length - 1];
System.out.println(lastWord);
