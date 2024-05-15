# MAGIC EDEN FREE NFT

Written by: @hvrsh (TG)

Channel: https://t.me/hashvers

---

**Automation of minting Magic Eden NFT**

**Configuration upon launching `meNftMint.xml`:**

1. Use Finger Switcher - Should fingerprints be used?
   1. Finger Print Key - If enabled with **1**, a key is required to obtain fingerprints, which can be purchased here - https://fingerprints.bablosoft.com/
2. Sleep - Time between accounts in the thread.
3. Clear DoneList - After successful completion or insufficient balance, private keys are recorded in the file `done_list.txt` so the software understands which accounts it has processed and which ones it hasn't. In case you interrupt its operation or a thread terminates with an error, and you need to rerun all wallets, select Yes.
4. Wallet shuffle - Should wallet shuffling be performed?
5. Moralis API - API for wallet balance checking. https://admin.moralis.io/settings#api_keys

 **Files for Operation:**

 `data.txt` - Specify addresses and seed phrases.

 `proxy.txt` - Proxies, listed line by line.


---

**Автоматизация минта NFT на платформе Magic Eden**

**Настройки при запуске `meNftMint.xml`:**

1. Use Finger Switcher - Следует ли использовать отпечатки пальцев?
   1. Finger Print Key - Если включено значение **1**, требуется ключ для получения отпечатков пальцев, который можно приобрести здесь - https://fingerprints.bablosoft.com/
2. Sleep - Время между аккаунтами в потоке.
3. Clear DoneList - После успешного завершения или недостаточного баланса ключи записываются в файл `done_list.txt`, чтобы программа понимала, какие аккаунты она обработала, а какие нет. В случае прерывания работы или ошибки потока, если вам нужно повторно запустить все кошельки, выберите `Yes`.
4. Wallet shuffle - Следует ли производить перемешивание кошельков?
5. Moralis API - API для проверки баланса кошелька.

 **Файлы для работы:**

 `data.txt` - Укажите адреса и сид-фразы.

 `proxy.txt` - Прокси, перечисленные построчно.
