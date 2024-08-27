# 🛒📊 PriceImageScraper

PriceImageScraper é uma ferramenta desenvolvida em Python que utiliza Selenium para buscar informações sobre preços e imagens de produtos em um site específico e armazená-las em uma planilha Excel. O projeto foi projetado para automatizar a coleta de dados de produtos e facilitar o monitoramento de preços e disponibilidade de estoque.

## 🛠️ Funcionalidades

- **Coleta automatizada de dados**: Busca informações de preços e imagens de produtos com base em uma lista de termos de pesquisa armazenados em uma planilha Excel.
- **Armazenamento em Excel**: Salva automaticamente os preços e links das imagens correspondentes a cada produto na planilha Excel.
- **Verificação de disponibilidade**: Detecta se um produto está fora de estoque e marca a planilha apropriadamente.

## 📂 Estrutura do Projeto

- **`PriceImageScraper.py`**: Script principal que realiza o scraping e armazena os dados.
- **`Produtos.xlsx`**: Planilha Excel onde os termos de pesquisa são inseridos e os resultados são armazenados.

## 🚀 Como Usar

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/AnubisChacal/PriceImageScraper.git
    ```

2. **Instale as dependências**:
    ```bash
    pip install selenium openpyxl
    ```

3. **Configure o script**:
   - Substitua a variável `url` no script com o URL do site que você deseja scraper.
   - Prepare a planilha `Produtos.xlsx` com os termos de pesquisa na coluna F (começando na linha 3).

4. **Execute o script**:
    ```bash
    python PriceImageScraper.py
    ```

5. **Resultados**:
   - Os preços e os links das imagens dos produtos serão armazenados na planilha `Produtos.xlsx`.

## 🛠️ Requisitos

- **Python 3.x**
- **Selenium**
- **Openpyxl**
- **Geckodriver** (para Firefox)

## 📝 Observações

- Este script foi desenvolvido para fins educacionais. Certifique-se de respeitar os termos de serviço dos sites ao utilizar web scrapers.
