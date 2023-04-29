meme_dict = {
            "CRINGE": "Garip ya da utandırıcı bir şey",
            "LOL": "Komik bir şeye verilen cevap",
            "ROFL" : "bir şakaya karşılık cevap",
            "SHEESH" : "onaylamamak",
            "CREEPY" : "korkunç",
            "AGGRO" : "agresifleşmek/sinirlenmek",
            }


while True:            
    word = input("Anlamadığınız bir kelime yazın (hepsini büyük harflerle yazın!): ")
    
    
    
    if word in meme_dict.keys():
        # Kelime eşleşiyorsa ne yapmalıyız?
        print(meme_dict[word])
    elif word == "YENİ KELİME":
        new_wordname=input("Yeni kelimenin adını giriniz:")
        new_worda=input("Yeni kelimenin anlamını giriniz:")
        meme_dict[new_wordname]=new_worda
        print("Başarılı işlem gerçekleştirilmiştir.")
    elif word == "QUIT":
        break
    else:
        # Kelime eşleşmiyorsa ne yapmalıyız?
        print("Lütfen başka bir kelime deneyin.")
    
    
print("Görüşürüz...")
