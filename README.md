# 🦷 Identificação de Dentes pela Numeração (Odontologia)

Este projeto implementa um sistema em Python para identificar dentes a partir da **numeração odontológica** (quadrante + número do dente).  
Através de um dicionário que representa a **arcada dentária**, o usuário pode digitar um número e obter automaticamente o nome do dente correspondente.

## 📌 O que o código faz
- Define um dicionário (`Arcada_Dentaria`) com todos os dentes, numerados de acordo com a notação odontológica.  
- Solicita ao usuário que digite a numeração de um dente.  
- Verifica se a numeração informada existe no dicionário:  
  - Caso exista, retorna o **nome do dente**.  
  - Caso não exista, informa que a numeração não corresponde a nenhum dente.  

## 🗂️ Numeração dos dentes cadastrados

| Numeração | Nome do Dente |
|-----------|----------------|
| **11** | Incisivo central superior direito |
| **12** | Incisivo lateral superior direito |
| **13** | Canino superior direito |
| **14** | Primeiro pré-molar superior direito |
| **15** | Segundo pré-molar superior direito |
| **16** | Primeiro molar superior direito |
| **17** | Segundo molar superior direito |
| **18** | Terceiro molar superior direito (siso) |
| **21** | Incisivo central superior esquerdo |
| **22** | Incisivo lateral superior esquerdo |
| **23** | Canino superior esquerdo |
| **24** | Primeiro pré-molar superior esquerdo |
| **25** | Segundo pré-molar superior esquerdo |
| **26** | Primeiro molar superior esquerdo |
| **27** | Segundo molar superior esquerdo |
| **28** | Terceiro molar superior esquerdo (siso) |
| **31** | Incisivo central inferior esquerdo |
| **32** | Incisivo lateral inferior esquerdo |
| **33** | Canino inferior esquerdo |
| **34** | Primeiro pré-molar inferior esquerdo |
| **35** | Segundo pré-molar inferior esquerdo |
| **36** | Primeiro molar inferior esquerdo |
| **37** | Segundo molar inferior esquerdo |
| **38** | Terceiro molar inferior esquerdo (siso) |
| **41** | Incisivo central inferior direito |
| **42** | Incisivo lateral inferior direito |
| **43** | Canino inferior direito |
| **44** | Primeiro pré-molar inferior direito |
| **45** | Segundo pré-molar inferior direito |
| **46** | Primeiro molar inferior direito |
| **47** | Segundo molar inferior direito |
| **48** | Terceiro molar inferior direito (siso) |

Digite a numeração do dente procurado (Numeração do quadrante + Numeração do dente): 11
O dente Procurado é: Incisivo central superior direito

## 🚀 Como executar
1. Tenha o Python instalado em sua máquina.  
2. Execute o script:
   ```bash
   python Odonto.py
