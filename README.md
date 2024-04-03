# PLN_Intelig._Artificial
Este trabalho foi desenvolvido durante uma disciplina de Inteligência Artificial do curso de Informática na Universidade Estadual de Maringá, este trabalha tem por objetivo utilizar os conhecimentos adquiridos sobre o tema Processamento de Linguagem Natural, para fazer a leitura de diversos artigos científicos adquiridos do site IEEExplore. 

## Testing Procedures

### Test Setup

To execute the tests, ensure the following prerequisites are met:

1. **File Organization:** The `artigos` folder containing the articles should be placed in the same directory as the code. This allows for proper file access during testing.

2. **Required Tools:** The following tools are necessary for running the tests:

   * Python: Install a compatible version of Python on your system.

   * PyPDF2: Install the `PyPDF2` library using pip: `pip install PyPDF2`

   * Matplotlib (Optional): Install the `Matplotlib` library using pip for graphical representation (if using `PLN_grafico.py`): `pip install matplotlib`
  
### Test Execution

To run the tests, follow these steps:

1. **Leitor_pdf.py and Busca_bm25.py:**

   Open a terminal window and navigate to the directory containing the code.

   Execute the following commands to run the tests:
   * python leitor_pdf.py
   * python busca_bm25.py

2. **PLN_grafico.py (Optional):**

   If you want to run the graphical version of the code, execute the following command in the terminal:
   * python PLN_grafico.py
   
   The graphical interface will display the extracted information and allow you to interact with the results.

### Additional Notes

- The tests are designed to extract specific information from the provided articles.

- The `busca_bm25.py` script allows users to search for specific terms within the articles.

- The `PLN_grafico.py` script provides a graphical interface for interacting with the extracted information.
