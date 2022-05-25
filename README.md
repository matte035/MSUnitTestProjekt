# MSUnitTestProjekt

Jag skall testa vår kod och några utav våra kritiska delar av projektet.

Jag har valt att testa "Deposit metoden", "CreateNewBankAccount, "WithdrawMoney metoden".

Vad jag tror kan gå fel i dessa kodblock som jag skall göra tester på:

Deposit metoden :
Om kunden inte har valt rätt valuta så går de inte genom eller har valt en negativt tal så fungerar inte koden.

CreateNewBankAccount metoden:
Om du vill ha ditt konto i en utländsvaluta som inte finns så går det inte att skapa kontot.

WithdrawMoney metoden:
Här ser jag ett kritiskt moment om summan inte anges i rätt valuta eller negativt tal så fungerar inte koden.
