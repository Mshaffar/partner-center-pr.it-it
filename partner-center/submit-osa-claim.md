---
title: Creare un'associazione cliente usando il modello CPOR | Centro per i partner
ms.topic: article
ms.date: 10/29/2019
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Creare un'associazione cliente usando il modello CPOR
author: LauraBrenner
ms.author: labrenne
keywords: attestazioni per incentivi, attestazioni co-op, fondi co-op, OSU, OSA, ISV, associazione di ricavi
ms.localizationpriority: medium
ms.openlocfilehash: a3515c0fff52c9083bbad6cd19f033a88ae2f38a
ms.sourcegitcommit: 1c3d3b95135e1daad5ba5585a090e84ab0b97594
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/22/2019
ms.locfileid: "74384880"
---
# <a name="create-a-customer-association-using-the-cpor-model"></a>Creare un'associazione cliente usando il modello CPOR

**Si applica a**

-  Centro per i partner


Il 1 ° ottobre 2019, Microsoft ha iniziato a usare il modello CPOR (Claiming partner of record) per gestire le associazioni con i clienti Microsoft 365 e Dynamics 365 per quanto concerne i servizi online Advisor (OSA) sell, Online Services Usage (OSU)- Microsoft 365 e OSU-incentivi per le applicazioni aziendali.

Quando si invia l'attestazione, Microsoft la convalida. A questo punto, è possibile che vengano richieste altre informazioni. Verrà inoltre inviata una notifica al cliente della richiesta di associazione. I clienti hanno cinque giorni lavorativi per rifiutare esplicitamente. Se non si rifiutano esplicitamente, l'associazione a questo tenant e carico di lavoro specifici sarà ufficiale. A questo punto sarà possibile accedere ai dati di utilizzo del cliente. 

Per completare un'attestazione, sono necessarie le informazioni seguenti:

- **ID MPN** per l'entità che rilascia l'attestazione

- Il **nome di dominio** del cliente [trova questo](https://docs.microsoft.com/partner-center/find-customer-domain-name)

- **ID directory** o **ID tenant** [](https://docs.microsoft.com/partner-center/find-customer-domain-name) del cliente

- **Area della soluzione**, ad esempio Business Applications o Microsoft 365

- L' **attività** eseguita e il tipo di attestazione che si desidera effettuare, ad esempio pre-vendite, utilizzo o associazione dei ricavi

- Il nome del **contatto**, il titolo e l'indirizzo di posta elettronica del cliente

- Per Dynamics 365, è anche necessario fornire il nome del **contatto tecnico** , il titolo e l'indirizzo di posta elettronica del cliente

- **Nome del contatto** e indirizzo di posta elettronica dell'azienda

- Verrà creato un **nome** per questa attestazione

- Il **prodotto** o i carichi di lavoro che si sta reclamando

- **Proof of Execution (PoE)** , ad esempio un rendiconto di lavoro firmato dal cliente. È anche possibile scaricare un modello POE da usare.

- Per i partner che rivendicano solo l'associazione dei ricavi: **nome del venditore della soluzione Dynamics**, **nome del cliente**e **nome della soluzione o del prodotto ISV**. 

È inoltre necessario comprendere i punti seguenti:
- Se si dispone di Microsoft 365 clienti esistenti, sarà necessario riassociarli a quelli per i quali si desidera continuare a ottenere incentivi OSU utilizzando questo processo.
- Se si dispone di associazioni esistenti con i clienti di Dynamics 365 o Power BI, queste associazioni rimarranno valide fino alla scadenza delle sottoscrizioni.
- Un cliente può avere più partner, ma ogni carico di lavoro (per OSU-Microsoft 365) o per la sottoscrizione (per OSA-sell e OSU-Business Applications) può essere associato solo a un partner.

## <a name="create-a-customer-association"></a>Creare un'associazione cliente
1.  Nel dashboard del centro per i partner, in **incentivi**selezionare **Panoramica**, quindi selezionare **associazioni clienti**. 

2.  Nella parte superiore della pagina associazioni clienti selezionare **+ associazione clienti**.

3.  Selezionare l' **ID MPN** della località partner da associare al cliente, quindi aggiungere il nome di dominio e l'ID directory del cliente. [Dove si trovano?](https://docs.microsoft.com/partner-center/find-customer-domain-name)

Seleziona **Continua**.

4.  Selezionare l' **area** e l' **attività**della soluzione. 

>[!Note]

>Se si seleziona Business Applications, selezionare **utilizzo e/o pre-vendite**o **associazione ricavi**, quindi selezionare **continua**. 

>Se si seleziona l'associazione di ricavi, verranno richieste informazioni leggermente diverse da quelle elencate di seguito. 

5.  Immettere le informazioni appropriate nella pagina **associa cliente** , quindi selezionare **Crea attestazione**.

6.  Selezionare il prodotto o i prodotti associati a questa associazione cliente, quindi selezionare **continua**.

7.  Completare le informazioni di contatto del cliente e le informazioni di contatto della società. Tutti i campi sono obbligatori. 

>[!Note]

Se il prodotto è Dynamics 365 e il prodotto scelto ha più sottoscrizioni per questo particolare cliente, sarà necessario immettere anche l'ID sottoscrizione.

8.  Fornire la prova di esecuzione (POE). È possibile trascinarlo nella casella, passare alla documentazione di supporto o usare un modello selezionando **Scarica modello**. 

9.  Aggiungere e salvare i commenti se lo si desidera, quindi selezionare **Invia attestazione**. Invieremo un messaggio di posta elettronica al cliente per richiedere l'approvazione dell'associazione del cliente. 

>[!NOTE]

>Una volta inviata l'associazione del cliente, non è possibile modificarla. 

Lo stato dell'associazione del cliente viene visualizzato nel campo **stato** . 

Selezionare **cronologia** per visualizzare la cronologia di un'associazione del cliente.
