# aula2

// Definição de uma interface chamada "Veiculo"
public interface Veiculo {
    // Métodos que as classes que implementam esta interface devem fornecer
    void acelerar(int velocidade);
    void frear(int intensidade);
    void ligar();
    void desligar();
}

// Classe Carro implementando a interface Veiculo
public class Carro implements Veiculo {
    @Override
    public void acelerar(int velocidade) {
        // Implementação específica para acelerar um carro
    }

    @Override
    public void frear(int intensidade) {
        // Implementação específica para frear um carro
    }

    @Override
    public void ligar() {
        // Implementação específica para ligar um carro
    }

    @Override
    public void desligar() {
        // Implementação específica para desligar um carro
    }
}

// Classe Bicicleta implementando a interface Veiculo
public class Bicicleta implements Veiculo {
    @Override
    public void acelerar(int velocidade) {
        // Implementação específica para acelerar uma bicicleta
    }

    @Override
    public void frear(int intensidade) {
        // Implementação específica para frear uma bicicleta
    }

    @Override
    public void ligar() {
        // Implementação específica para ligar uma bicicleta (não faz sentido em uma bicicleta)
    }

    @Override
    public void desligar() {
        // Implementação específica para desligar uma bicicleta (não faz sentido em uma bicicleta)
    }
}
