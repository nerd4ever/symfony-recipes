# Nerd4ever Symfony Flex Recipes
Este repositório contém as receitas do Symfony Flex para os bundles da Nerd4ever.

## O que é uma receita Symfony Flex?
Uma receita Symfony Flex é um conjunto de instruções automatizadas para configurar um bundle Symfony. Quando um bundle é instalado através do Composer, o Symfony Flex procura por uma receita correspondente e a aplica à aplicação Symfony. Uma receita pode definir quais bundles devem ser habilitados, quais arquivos devem ser copiados e quais variáveis de ambiente devem ser definidas.

## Uso
Para usar estas receitas em seu projeto Symfony, você precisa adicionar este repositório como um repositório de receitas personalizado. Adicione a seguinte configuração ao seu arquivo `composer.json`:

````
{
    "extra": {
        "flex": {
            "recipes": [
                "https://github.com/nerd4ever/symfony-recipes.git"
            ]
        }
    }
}
````
Após essa configuração, quando você instalar um bundle da Nerd4ever via Composer, o Symfony Flex procurará uma receita correspondente neste repositório.


## Licença
Todos os direitos reservados à Nerd4ever. Este projeto é de propriedade da Nerd4ever e não pode ser copiado ou reproduzido sem a permissão explícita da Nerd4ever.
