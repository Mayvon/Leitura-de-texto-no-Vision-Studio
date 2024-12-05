## **README.md**

```markdown
# Reconhecimento Óptico de Caracteres (OCR) com o Azure Vision Studio

Este projeto demonstra como usar as capacidades de OCR do Azure Vision Studio para extrair e analisar texto de imagens. O processo envolve o upload de imagens, a execução da análise OCR e a revisão dos dados de texto estruturados e caixas delimitadoras.

---

## **Visão Geral do Processo**

1. **Configuração dos Serviços de IA no Azure**:
   - Criado um recurso de IA do Azure com capacidades do Vision Studio.
   - Configurado o recurso no Vision Studio para habilitar o OCR.

2. **Upload e Análise das Imagens**:
   - Utilizadas imagens de exemplo fornecidas no [tutorial de OCR do Microsoft Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html).
   - Imagens analisadas:
     - `advert.jpg`: Uma propaganda promocional com texto.
     - `letter.jpg`: Um documento digitalizado com texto digitado.
   - Executada a análise OCR para extrair dados de texto estruturados.

3. **Revisão dos Resultados**:
   - Texto identificado com precisão e caixas delimitadoras ao redor das áreas detectadas.
   - Dados organizados em uma hierarquia de **regiões**, **linhas** e **palavras**.

---

## **Insights e Observações**

- **Precisão**: O OCR reconheceu eficientemente texto impresso e manuscrito, organizando-o em um formato estruturado.
- **Utilidade**: Pode ser aplicado para digitalizar documentos, automatizar entrada de dados e melhorar a acessibilidade.
- **Visualização de Caixas Delimitadoras**: Áreas de texto destacadas foram marcadas com precisão, demonstrando as capacidades de detecção espacial do OCR.
- **Facilidade de Uso**: A interface do Vision Studio simplifica os testes sem necessidade de escrever código.

---

## **Imagens e Resultados de Exemplo**

### Antes do Processamento
#### Imagem da Propaganda:
![Propaganda](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/images/advert.jpg)

#### Imagem da Carta:
![Carta](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/images/letter.jpg)

### Após o Processamento
#### Texto Detectado com Caixas Delimitadoras:
- Propaganda:
  ```
  Northwind Traders
  Grand Opening Sale
  Save up to 50%!
  ```
- Carta:
  ```
  Prezado(a) Senhor(a),
  Temos o prazer de confirmar sua aplicação...
  ```

---

## **Possibilidades Futuras**

- Integração em aplicativos web ou móveis para tarefas de OCR em tempo real.
- Automação aprimorada para processamento de formulários e análise de documentos.
- Combinação do OCR com APIs de tradução para reconhecimento de texto multilíngue.

---

Para mais detalhes, visite a [página do tutorial de OCR](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html).
```

---

Se precisar de ajustes ou outras informações, é só pedir! 😊
