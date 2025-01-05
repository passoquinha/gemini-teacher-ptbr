# Gemini 英语口语助手

Este é um assistente de prática de inglês baseado no Google Gemini AI, que pode reconhecer sua pronúncia em inglês em tempo real e fornecer feedback instantâneo e sugestões de correção。

Make by [Box](https://x.com/boxmrchen)

## Características:

- 🎤 Reconhecimento de fala em tempo real
- 🤖 Avaliação de pronúncia orientada por IA
- 📝 Correção gramatical
- 🔄 Exercícios de diálogo situacional
- 🎯 Orientação de pronúncia direcionada
- 💡 Troca de cena inteligente

## Requisitos do sistema:

- Python 3.11+ (Necessário)
- Microfone
- Conexão à Internet

## Dependências:

Você precisa de uma chave de API Gemini, que é gratuita 4 milhões de vezes por dia, o que é suficiente para usar。

Vá para esta página [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey) Basta gerá-la。

## Instalação:

1. Clonar repositório：
```bash
git clone https://github.com/nishuzumi/gemini-teacher.git
cd gemini-teacher
```

2. Crie e ative um ambiente virtual（Recomendado）：
```bash
python -m venv .venv
source .venv/bin/activate  # Unix/macOS
# ou
.venv\Scripts\activate  # Windows
```

3. Instale dependências：

Antes de instalar as dependências do Python, instale as seguintes dependências do sistema：

- Windows: Nenhuma instalação adicional necessária
- macOS: `brew install portaudio`
- Ubuntu/Debian: `sudo apt-get install portaudio19-dev python3-pyaudio`

```bash
pip install -r requirements.txt
```

## Como usar:

1. Configurar o ambiente
Crie um novo arquivo `.env`, copie o `.env.example` e modifique-o。

Se você precisar configurar um proxy, preencha `HTTP_PROXY`, por exemplo, `HTTP_PROXY=http://127.0.0.1:7890`

`GOOGLE_API_KEY` Preencha o Google Gemini Api Key
### Ativar voz
Esta função é habilitada sob demanda, `ELEVENLABS_API_KEY` é a API KEY para a função de voz。

Como obtê-la：
- Abra o site [https://elevenlabs.io/](https://try.elevenlabs.io/2oulemau2lxk)
- Clique no canto superior direito "Try for free"，Inscreva-se e ganhe 1000 créditos gratuitamente
- Acesse as configurações pessoais, gere a chave API e preencha-a

```bash
python starter.py
```

2. Siga as instruções para falar frases em inglês
3. Aguarde o feedback do assistente de IA
4. Melhore a pronúncia com base no feedback

## Instruções interativas

- 🎤 : Gravação
- ♻️ : Processamento
- 🤖 : Feedback de IA

## licença

MIT

## contribuir

Submissões Issue são bem vindas e Pull Request！
