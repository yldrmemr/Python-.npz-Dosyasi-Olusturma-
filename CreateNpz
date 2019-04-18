# -*- coding: utf-8 -*-
"""
Created on Fri Mar 29 22:58:28 2019

@author: Dell
"""

"""*************************************************************************
*           İmport Edilecek Kütüphaneler 
*
*************************************************************************"""
import numpy as np


"""************************************************************************
*     Burada Rastgele Diziler Tanımlandı 
*
************************************************************************"""
x = np.arange(100)
y = np.sin(x)
z= np.cos(x)
k = np.zeros(shape=(5,2)) # sıfırlardan olusan 5x2 lik matris olusturma 

"""**********************************************************************
*              Okuma ve Yazma İşlemleri Burdan Sonra Yapılıyor 
*
**********************************************************************"""

np.savez('Deneme.npz', Sin=y, Cos=z, Matris= k, Deger= x) # deneme.npz ismiyle kaydedildi 
Read = np.load('Deneme.npz') # Aynı isimle okunup Read isimli degiskene atandı 
print(Read['Sin'])
print (Read['Cos'])
print (Read.files) # bu komutlada dosya içerisinde ne isimli dosyalar oldugunu görebiirsiniz 


