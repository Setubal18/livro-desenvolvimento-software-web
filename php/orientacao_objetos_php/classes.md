#Classes
Uma classe permite representar uma abstração genérica de um determinado universo, isto é, permite representar um conjunto de itens (objetos) com características similares em uma única representação. Assim, considerando que toda e qualquer possui um *Cpf* e um *Nome*, a seguir é apresentado um exemplo da definição de uma classe Pessoa. 
```php
<?php
class Pessoa
{
    private $cpf;
    private $nome;

    public function getCpf()
    {
        return $this->cpf;
    }

    public function setCpf($cpf)
    {
        $this->cpf = $cpf;
    }

    public function getNome()
    {
        return $this->nome;
    }

    public function setNome($nome)
    {
        $this->nome = $nome;
    }   
}
```
Na classe `Pessao` definida anteriormente, foram definidos os métodos **Getters** e **Setters**, que possibilitam acessar e definir os atributos da classe. Os seus atributos são `$cpf` e `$nome`.