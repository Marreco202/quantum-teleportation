# Quantum Teleportation

Implementação em Python do protocolo de **Teletransporte Quântico** (Bennett et al.), utilizando o framework [Qiskit](https://qiskit.org/), explorando tanto o cenário *incompleto* (sem comunicação clássica) quanto a versão *completa* do protocolo.

O trabalho aborda:

1. **Parte 1 – Protocolo incompleto**  
   - Simulação sem comunicação clássica.  
   - Discussão sobre por que não há transmissão de informação mais rápida que a luz.  

2. **Parte 2 – Protocolo completo**  
   - Implementação do circuito com 3 qubits e comunicação clássica.  
   - Aplicação de portas condicionais em Bob, de acordo com o resultado de Alice.  
   - Demonstração experimental de que as probabilidades do estado de Alice foram corretamente teleportadas para o qubit de Bob.  

Além disso, o notebook analisa o **Teorema da Não-clonagem**, mostrando que não há duplicação do estado original, apenas transferência de informação.

## ⚙️ Dependências
- [Python 3.9+](https://www.python.org/)  
- [Qiskit](https://qiskit.org/)  
- [NumPy](https://numpy.org/)  
- [python-dotenv](https://pypi.org/project/python-dotenv/)  


## ▶️ Como executar

1. Clone este repositório:

```bash
git clone https://github.com/Marreco202/quantum-teleportation.git
```

2. Crie um ambiente virtual com sua ferramenta de preferência (Conda/pyenv)

```bash
pyenv install 3.9
cd quantum-teleportation
pyenv local 3.9
python --version
# Python 3.9.23
```

>Devido ao uso de algumas bibliotecas, é recomnedado utilizar alguma versão do Python 3.9+ para a execução do notebook

3. Instale todas as dependências
```bash
pip install qiskit numpy python-dotenv
```

4. Execute as células do notebook sequencialmente para obter os resultados do experimento! 

## 👥 Autores

- [João V. G. Woitschach](https://github.com/Marreco202/)
- [Jerônimo Augusto Soares](https://github.com/Perguntador)  
