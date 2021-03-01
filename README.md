# Chatbot based on hugging face.

## To install dependencies:

```
pip3 install -r requirements.txt
```

## To get models:

```
curl https://s3.amazonaws.com/models.huggingface.co/transfer-learning-chatbot/finetuned_chatbot_gpt.tar.gz > models/finetuned_chatbot_gpt.tar.gz
```

then

```
cd models
```

and

```
tar -zxvf finetuned_chatbot_gpt.tar.gz
```

## To run:

```
python3 interact.py --model ./models --max_history 10000
```
