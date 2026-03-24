import java.util.Scanner;

public class Exercicio_12 {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        int menu = 0;
        int menu2 = 0;

        while(true) {
            System.out.println("Escolha a opção desejada:");
            System.out.println("1 - Temperadura");
            System.out.println("2 - Distância");
            System.out.println("3 - Peso");
            System.out.println("4 - Sair");

            if(!scanner.hasNextInt()) {
                System.out.println("Entrada inválida, digite opção correta!");
                scanner.next();
                continue;
            }

            menu = scanner.nextInt();
            if(menu < 1 || menu > 4) {
                System.out.println("Menu inválido, tente novamente!");
                continue;
            } else if (menu == 4) {
                System.out.println("Obrigado e até breve!");
                break;
            }

            switch (menu) {
                case 1:
                    while(true) {
                        System.out.println("Escolha a opção para converter:");
                        System.out.println("1 - Celsius para Fahrenheit ");
                        System.out.println("2 - Celsius para Kelvin");
                        System.out.println("3 - Voltar ao menu anterior");

                        if(!scanner.hasNextInt()) {
                            System.out.println("Entrada inválida, digite opção correta!");
                            scanner.next();
                            continue;
                        }

                        menu2 = scanner.nextInt();
                        if(menu2 < 1 || menu2 > 3) {
                            System.out.println("Menu inválido, tente novamente!");
                            continue;
                        } else if (menu2 == 3) {
                            break;
                        }

                    switch (menu2) {
                        case 1:
                            System.out.println("Digite a temperatura em Celsius");
                                    if (!scanner.hasNextDouble()) {
                                    System.out.println("Entrada errada, digite novamente!");
                                    scanner.next();
                                } else {
                                    double celsius = scanner.nextDouble();
                                        System.out.println("Temperatura em Fahrenheit: " + (celsius * 9.0 / 5.0 + 32) + "°F");
                                    break;
                                }

                        case 2:
                            System.out.println("Digite a temperatura em Celsius");
                            if (!scanner.hasNextDouble()) {
                                System.out.println("Entrada errada, digite novamente!");
                                scanner.next();
                            } else {
                                double Celsius = scanner.nextDouble();
                                System.out.println("Temperatura em Kelvin: " + (Celsius + 273.15) + "°K");
                                break;
                            }

                        }

                    }break;

                case 2:
                    while(true) {
                        System.out.println("Escolha a opção para converter:");
                        System.out.println("1 - Km para Milhas");
                        System.out.println("2 - Km para Metros");
                        System.out.println("3 - Voltar ao menu anterior");

                        if(!scanner.hasNextInt()) {
                            System.out.println("Entrada inválida, digite opção correta!");
                            scanner.next();
                            continue;
                        }

                        menu2 = scanner.nextInt();
                        if(menu2 < 1 || menu2 > 3) {
                            System.out.println("Menu inválido, tente novamente!");
                            continue;
                        } else if (menu2 == 3) {
                            break;
                        }

                        switch (menu2) {
                            case 1:
                                System.out.println("Digite o Km para converter");
                                if (!scanner.hasNextDouble()) {
                                    System.out.println("Entrada errada, digite novamente!");
                                    scanner.next();
                                } else {
                                    double km = scanner.nextDouble() * 0.621371;
                                    System.out.println("O km em Milhas é: " + km + " Milhas");
                                    break;
                                }

                            case 2:
                                System.out.println("Digite o Km para converter");
                                if (!scanner.hasNextDouble()) {
                                    System.out.println("Entrada errada, digite novamente!");
                                    scanner.next();
                                } else {
                                    double km = scanner.nextDouble() * 1000;
                                    System.out.println("O km em metros é: " + km + " Metros");
                                    break;
                                }

                            }

                    }break;

                case 3:
                    while(true) {
                        System.out.println("Escolha a opção para converter:");
                        System.out.println("1 - Kg para Libras");
                        System.out.println("2 - Kg para Gramas");
                        System.out.println("3 - Voltar ao menu anterior");

                        if(!scanner.hasNextInt()) {
                            System.out.println("Entrada inválida, digite opção correta!");
                            scanner.next();
                            continue;
                        }

                        menu2 = scanner.nextInt();
                        if(menu2 < 1 || menu2 > 3) {
                            System.out.println("Menu inválido, tente novamente!");
                            continue;
                        } else if (menu2 == 3) {
                            break;
                        }

                        switch (menu2) {
                            case 1:
                                System.out.println("Digite o Kg para converter");
                                if (!scanner.hasNextDouble()) {
                                    System.out.println("Entrada errada, digite novamente!");
                                    scanner.next();
                                } else {
                                    double kg = scanner.nextDouble() * 2.20462;
                                    System.out.println("O kg em Libras é: " + kg + " Libras");
                                    break;
                                }

                            case 2:
                                System.out.println("Digite o Kg para converter");
                                if (!scanner.hasNextDouble()) {
                                    System.out.println("Entrada errada, digite novamente!");
                                    scanner.next();
                                } else {
                                    double kg = scanner.nextDouble() * 1000;
                                    System.out.println("O kg em Gramas é: " + kg + " Gramas");
                                    break;
                                }

                        }

                    }break;


            }
    }



        scanner.close();
    }
}
