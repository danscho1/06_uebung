# Übung - 06: Reinforcement Learning

## Ziel der Übung

- n-armed Bandit Problem
- Tic Tac Toe Ansatz
- Setup OpenAi Gym Environments und testen eines einfachen Beispiels

---

## Aufgabe 1

Verwenden sie das [Jupyter Notebook](bandit.ipynb) zum n-armed Bandit und vergleichen sie 5 verschiedene epsilon-greedy-Werte. Importieren Sie hierz das Notebook in ihre Umgebung.

## Aufgabe 2

OpenAI ist eine Non-Profit-Organisation, die sich mit der Erforschung von künstlicher Intelligenz (KI, englisch Artificial Intelligence, AI) beschäftigt.

Ab 2016 hat OpenAI ihre Plattform „OpenAI Gym“ entwickelt, die sich mit bestärkendem Lernen (en: reinforcement learning) befasst. Der Quellcode ist in seiner aktuellen Version auf GitHub abrufbar (https://github.com/openai/gym). Dabei wird angestrebt ein Basissystem anzubieten, das leicht aufzusetzen ist und eine große Bandbreite an verschiedenen Entwicklungsumgebungen unterstützt. OpenAI Gym versucht damit eine Standardisierung für die Veröffentlichung von Ergebnissen in der Erforschung von künstlicher Intelligenz anzubieten, um Publikationen leichter vergleichen und reproduzieren zu können


Installieren Sie die OpenAi Gym Umgebung auf ihrem Computer. Folgen Sie der Anweisung hier: [Gym](https://github.com/openai/gym).

Moeglicherweise reicht ein 

        pip install gym

in ihrere Anaconda Umgebung.

Alternative koennen Sie auch eine Vm in unserer Azure Subscription aufsetzen und das OpenAi Gym dort installieren.

Testen Sie ihre installation mit dem Python Skript [Cartpole](cartpole.py).

## Aufgabe 3


Gegeben st das [Tic Tac Toe](tic_tac_toe.ipynb) Skript. 

1. Handelt es sich hierbei um Reinforcement Learning? Diskutieren sie mit ihrem Nachbarn. 
2. Welcher Ansatz wird hier verfolgt: Policy- oder Value-Based oder etwas anderes?
3. Ab welcher Anzahl von Trainings-Iterationen ist ein Unentschieden oder Sieg mit einer Wahrscheinlichkeit von >90% gegeben?