from docx import Document

# Criar o documento de requisitos
doc = Document()

# Título principal
doc.add_heading('Documento de Requisitos de Software (DRS)', level=1)
doc.add_paragraph("Projeto: Biblioteca Virtual Inteligente")
doc.add_paragraph("Versão: 1.0")
doc.add_paragraph("Data: 04/12/2024")

# Seção 1 - Introdução
doc.add_heading('1. Introdução', level=2)
doc.add_paragraph('1.1 Propósito')
doc.add_paragraph('O propósito deste documento é definir os requisitos funcionais e não funcionais do sistema Biblioteca Virtual Inteligente.')

doc.add_paragraph('1.2 Escopo')
doc.add_paragraph('O sistema será utilizado para gerenciar um acervo digital de livros, permitindo buscas, reservas e downloads, além de recomendações personalizadas.')

doc.add_paragraph('1.3 Definições, Acrônimos e Abreviações')
doc.add_paragraph('- DRS: Documento de Requisitos de Software\n- UML: Unified Modeling Language')

doc.add_paragraph('1.4 Referências')
doc.add_paragraph('- Fowler, M. UML Essencial: Um breve guia para linguagem padrão, 3ª ed., Porto Alegre: Bookman, 2005.\n'
                  '- Sommerville, I. Engenharia de Software, 10ª ed., São Paulo: Pearson, 2018.\n'
                  '- Larman, C. Utilizando UML e Padrões, Porto Alegre: Bookman, 2011.')

# Seção 2 - Descrição Geral
doc.add_heading('2. Descrição Geral', level=2)
doc.add_paragraph('2.1 Perspectiva do Produto')
doc.add_paragraph('O sistema fornecerá funcionalidades básicas para busca, reserva, download de livros e recomendações.')

doc.add_paragraph('2.2 Funções do Produto')
doc.add_paragraph('- Cadastro e login de usuários\n- Busca no acervo\n- Reserva de livros físicos\n- Download de e-books\n- Recomendação de livros')

doc.add_paragraph('2.3 Usuários do Sistema')
doc.add_paragraph('Usuários finais: leitores e administradores do acervo.')

doc.add_paragraph('2.4 Restrições')
doc.add_paragraph('O sistema deve estar disponível para dispositivos móveis e navegadores modernos.')

# Seção 3 - Requisitos Específicos
doc.add_heading('3. Requisitos Específicos', level=2)

doc.add_paragraph(

doc
'3.1 Requisitos Funcionais')
doc.add_paragraph(
doc
'1. O sistema deve permitir o cadastro e login de usuários.\n'
                  '2. O sistema deve possibilitar buscas por livros no acervo.\n'
                  '3. O sistema deve oferecer recomendações personalizadas com base nos hábitos de leitura.\n'
                  
                 
'4. O sistema deve permitir a reserva de livros físicos.\n'
                  
                 
'5. O sistema deve possibilitar o download de e-books.')

doc.add_paragraph('3.2 Requisitos Não Funcionais')
doc.add_paragraph(
doc.add_paragraph


'1. O sistema deve garantir tempo de resposta inferior a 2 segundos para buscas.\n'
                  

'2. O sistema deve suportar até 10.000 usuários simultâneos.\n'
                  '3. O sistema deve implementar criptografia de senhas.\n'
                  '4. O sistema deve ser compatível com dispositivos móveis.')

# Anexar diagrama de casos de uso
doc.add_heading(

'4. Anexos', level=2)
doc.add_paragraph(
doc.add
'Abaixo, está o diagrama de casos de uso referente ao sistema Biblioteca Virtual Inteligente.')

# Inserir o diagrama no documento
doc.add_picture(
doc.add
'/mnt/data/diagrama_casos_de_uso.png', width=docx.shared.Inches(5.5))

# Salvar o documento
doc_path = 
doc_path =
"/mnt/data/DRS_Biblioteca_Virtual.docx"
doc.save(doc_path)
doc_path

doc.save(doc_path)
doc

doc.save
