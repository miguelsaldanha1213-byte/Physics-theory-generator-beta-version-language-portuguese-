import random

print("🤖 IA Teórica iniciada (digite 'sair' para parar)\n")

respostas = {
    "oi": ["Oi!", "Olá, humano.", "E aí 😄"],
    "quem é você": [
        "Sou uma IA criada para gerar teorias.",
        "Uma inteligência experimental.",
        "Algo entre código e imaginação."
    ],
    "teoria": [
        "Talvez tudo seja uma simulação.",
        "E se a realidade fosse editável?",
        "Nada garante que o tempo seja linear."
    ]
}

while True:
    user = input("Você: ").lower()

    if user == "sair":
        print("IA: Encerrando conversa...")
        break

    resposta = None
    for chave in respostas:
        if chave in user:
            resposta = random.choice(respostas[chave])
            break

    if resposta is None:
        resposta = random.choice([
            "Interessante... continue.",
            "Explique melhor essa ideia.",
            "Isso pode virar uma teoria."
        ])

    print("IA:", resposta)
