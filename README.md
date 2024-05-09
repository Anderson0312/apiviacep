
# Atualizador de CEPs para Planilha Excel

Este script Python foi desenvolvido para automatizar a tarefa de atualização de CEPs em uma planilha do Excel. Ele consulta a API dos Correios para obter o CEP correspondente a partir de um endereço fornecido na planilha e atualiza a planilha com os CEPs obtidos.

## Pré-requisitos

* Python 3.x instalado
* Bibliotecas Python: `openpyxl` e `requests`. Você pode instalá-las executando `pip install openpyxl requests`.

## Como usar

1. Clone ou faça o download deste repositório em seu computador.
2. Coloque o arquivo Excel que você deseja atualizar na mesma pasta que o script (`atualizador_ceps.py`). Certifique-se de que o arquivo Excel contenha uma coluna com os endereços que você deseja consultar.
3. Abra um terminal ou prompt de comando na pasta onde você salvou os arquivos.
4. Execute o script Python com o comando:
   <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><div class="flex items-center"><span class="" data-state="closed"><button class="flex gap-1 items-center"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M12 3.5C10.8954 3.5 10 4.39543 10 5.5H14C14 4.39543 13.1046 3.5 12 3.5ZM8.53513 3.5C9.22675 2.3044 10.5194 1.5 12 1.5C13.4806 1.5 14.7733 2.3044 15.4649 3.5H17.25C18.9069 3.5 20.25 4.84315 20.25 6.5V18.5C20.25 20.1569 19.1569 21.5 17.25 21.5H6.75C5.09315 21.5 3.75 20.1569 3.75 18.5V6.5C3.75 4.84315 5.09315 3.5 6.75 3.5H8.53513ZM8 5.5H6.75C6.19772 5.5 5.75 5.94772 5.75 6.5V18.5C5.75 19.0523 6.19772 19.5 6.75 19.5H17.25C18.0523 19.5 18.25 19.0523 18.25 18.5V6.5C18.25 5.94772 17.8023 5.5 17.25 5.5H16C16 6.60457 15.1046 7.5 14 7.5H10C8.89543 7.5 8 6.60457 8 5.5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div><div class="overflow-y-auto p-4 text-left undefined" dir="ltr"><code class="!whitespace-pre hljs">python atualizador_ceps.py
   </code></div></div></pre>
5. O script começará a processar a planilha, consultando a API dos Correios para cada endereço e atualizando a planilha com os CEPs correspondentes.
6. Após a conclusão, o script salvará as alterações no arquivo Excel original.

## Observações

* Certifique-se de que os endereços na planilha estão formatados corretamente para consulta na API dos Correios.
* O script assume que os endereços estão na primeira coluna da planilha e que os CEPs serão escritos na segunda coluna. Você pode ajustar isso conforme necessário no código-fonte.
* Se ocorrerem erros durante a execução, o script os imprimirá no console para ajudar na depuração.

## Autor

Este script foi desenvolvido por Anderson moura e está disponível sob a licença MIT. Sinta-se à vontade para contribuir ou relatar problemas neste repositório.
