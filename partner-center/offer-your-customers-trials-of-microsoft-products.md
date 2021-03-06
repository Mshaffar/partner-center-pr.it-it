---
title: Offrire ai clienti versioni di valutazione dei prodotti Microsoft
ms.topic: article
ms.date: 05/04/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Consentire ai clienti di provare i prodotti di sottoscrizione Microsoft per 30 giorni. È sufficiente iscriversi a queste versioni di valutazione gratuite nel catalogo come molti altri Servizi online.
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 66ea888a8efa9b44ea98b36c4341ba88f9bd1f4c
ms.sourcegitcommit: e9b627159745bcce53a8c2b1676f63f5249bba76
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/07/2020
ms.locfileid: "82907356"
---
# <a name="give-customers-30-day-free-trials-of-microsoft-products"></a>Concedi ai clienti una versione di valutazione gratuita di 30 giorni dei prodotti Microsoft

**Si applica a**

- Centro per i partner

**Ruoli appropriati**
-   Amministratore globale 
-   Amministratore utenti
-   Agente di vendita

Un modo efficace per presentare i clienti ai nuovi prodotti Microsoft è quello di offrire versioni di valutazione gratuite di 30 giorni. È possibile iscriversi per le versioni di valutazione nel catalogo proprio come molti altri Servizi online. Tutti i partner.

## <a name="available-trial-offers"></a>Offerte di valutazione disponibili

Tutte le offerte di valutazione in attesa sono disponibili nella pagina del **cliente** . Questa pagina elenca tutte le sottoscrizioni, incluse le versioni di valutazione gratuite e quelle a pagamento. Questa funzionalità non è attualmente disponibile in Cina.

Ogni cliente ha diritto a una versione di valutazione gratuita per ogni offerta disponibile. Ad esempio, è possibile ottenere una versione di valutazione gratuita per Microsoft 365 Business standard e una versione di valutazione gratuita per Office 365 E3. Tuttavia, se il cliente è già proprietario dell'offerta, non potrà usare una versione di valutazione gratuita per l'offerta.

### <a name="available-products"></a>Prodotti disponibili

Sono disponibili versioni di valutazione gratuite per i seguenti prodotti:

- Microsoft 365 Business standard
- Office 365 E3
- Office 365 E5 con PSTN
- Office 365 E5 senza PSTN
- Enterprise Mobility & Security E5
- Piano di coinvolgimento clienti di Dynamics 365 1
- Dynamics 365 Business Central
- Microsoft 365 Business Premium

Offriamo versioni di valutazione gratuite per questi prodotti perché sono le offerte aziendali più complete e popolari. È possibile che in futuro siano disponibili altre offerte di versioni di valutazione gratuite.

Attualmente non sono disponibili **versioni di valutazione gratuite** per offerte per enti pubblici, offerte di formazione o offerte di componenti aggiuntivi.

## <a name="licenses-for-free-trial-offers"></a>Licenze per le offerte della versione di valutazione gratuita

Tutte le versioni di valutazione gratuite forniscono 25 licenze. Non è possibile modificare questo numero durante la versione di valutazione. Non è possibile aggiungere o rimuovere le postazioni nella versione di valutazione gratuita. Dopo che la versione di valutazione è stata convertita in una sottoscrizione a pagamento, è possibile aggiungere altre licenze alla sottoscrizione.

È consigliabile assegnare le licenze e le postazioni di valutazione esattamente come per un servizio a pagamento nel centro per i partner.

## <a name="sign-customers-up-for-trials"></a>Accedi ai clienti per le versioni di valutazione

Per firmare il cliente per una versione di valutazione tramite il centro per i partner:

1. Da **sell** nel centro per i partner passare a **Catalog**. 
2. Nel catalogo, in **frequenza di fatturazione**, fare clic su **offerta di valutazione**. Questo consente di visualizzare solo le versioni di valutazione gratuite e di disabilitare altre offerte non gratuite. Le versioni di valutazione vengono visualizzate nella scheda **test** nel catalogo.
3. Selezionare la versione di valutazione gratuita che si vuole offrire, quindi selezionare **Invia**. Tutte le versioni di valutazione sono di 30 giorni durante le quali non verrà addebitato alcun importo. È anche possibile convertirlo in una sottoscrizione a pagamento in qualsiasi momento durante la versione di valutazione.

## <a name="converting-trials-to-paid-subscriptions"></a>Conversione di versioni di valutazione in sottoscrizioni a pagamento

Una versione di valutazione gratuita non viene convertita automaticamente in una sottoscrizione a pagamento. Dopo trenta giorni, una versione di valutazione gratuita deve essere convertita in una sottoscrizione a pagamento o [scadrà](#expiring-offers). Non è possibile estendere le versioni di valutazione gratuite.

Dovrai convertire la versione di valutazione in una sottoscrizione a pagamento. Questa operazione può essere eseguita [tramite il centro](#convert-trials-using-partner-center) per i partner o [tramite le API del centro per i partner](#convert-trials-using-apis).

> [!NOTE]
> Le versioni di valutazione gratuite del cliente per il programma Cloud Solution Provider (CSP) non possono essere convertite in un altro tenant del programma (ad esempio EA, Open o MOSP).

### <a name="convert-trials-using-partner-center"></a>Converti le versioni di valutazione con il centro per i partner

È possibile convertire le versioni di valutazione in sottoscrizioni a pagamento usando il dashboard del centro per i partner come segue:

1. Visitare la pagina di sottoscrizione del cliente e selezionare la versione di valutazione gratuita.
2. Selezionare **Converti versione di valutazione a sottoscrizione a pagamento**.
3. Immettere la quantità di licenza e la frequenza di fatturazione desiderate e selezionare **applica**.
4. La fatturazione per la sottoscrizione a pagamento inizia alla data di conversione e la sottoscrizione auto rinnova i dodici mesi dalla data di conversione. 

### <a name="convert-trials-using-apis"></a>Convertire le versioni di valutazione usando le API

Potrebbe essere necessario modificare le API per adattarla alla conversione di una versione di valutazione gratuita a una sottoscrizione a pagamento. Per ulteriori informazioni, vedere la seguente documentazione per gli sviluppatori:

- [Convertire un abbonamento di valutazione in uno a pagamento](https://docs.microsoft.com/partner-center/develop/convert-a-trial-subscription-to-paid)
- [Ottenere un elenco delle offerte di conversione della copia di valutazione](https://docs.microsoft.com/partner-center/develop/get-a-list-of-trial-conversion-offers)

### <a name="trials-without-conversions"></a>Versioni di valutazione senza conversioni

Non tutte le versioni di valutazione possono essere convertite in sottoscrizioni a pagamento. I partner possono usare una versione di valutazione senza conversioni fino alla data di scadenza. I partner possono acquistare offerte compatibili che supportano gli stessi servizi dell'offerta di valutazione.  Questa operazione deve essere eseguita prima della scadenza della versione di valutazione per assicurarsi che i servizi delle offerte appena acquistate siano allineati ai servizi della versione di valutazione. 

|**Valutazione**   |**Offerte di piccole imprese compatibili**   |**Offerte aziendali compatibili**   |
|----------------------------|:---------------------------------|:------------------------------------------|
|Versione di valutazione del cloud commerciale Microsoft Teams (avviata dall'utente)   |Microsoft 365 Business Basic, Microsoft 365 Business standard, Microsoft 365 Business Premium   | F3 (in precedenza F1), Office 365 per Enterprise (E1, E3 e E5), M365 F1/F3, M365 Enterprise (E3)   |

>[!NOTE]
>Le offerte precedenti presentano piani di servizio simili con funzionalità simili, tuttavia potrebbero esserci alcune differenze tra le offerte.

### <a name="expiring-offers"></a>Offerte in scadenza

L'utente non riceverà alcuna notifica delle offerte in scadenza. È possibile tenere traccia delle date di scadenza future usando la visualizzazione clienti nel centro per i partner o eseguendo una query sull'API. È consigliabile monitorare queste date di frequente in modo da poter intraprendere le azioni appropriate quando si avvicinano i momenti critici in cui i clienti devono prendere una decisione.

Dopo la scadenza di una versione di valutazione, un cliente che tenta di accedere a tale versione di valutazione visualizzerà un messaggio di scadenza. Tuttavia, i dati vengono archiviati in linea con gli standard di conservazione dei dati. Dopo l'acquisto di una nuova sottoscrizione con gli stessi piani di servizio, è possibile accedere nuovamente alle informazioni del cliente dalla sottoscrizione appena attivata.

## <a name="billing"></a>Fatturazione

La fatturazione annuale e le versioni di valutazione gratuite sono le stesse nei cloud sovrani e nel cloud pubblico. L'unica differenza è rappresentata dagli SKU di valutazione disponibili al momento dell'avvio.

## <a name="billing-for-free-trials"></a>Fatturazione per le versioni di valutazione gratuite

Le versioni di valutazione gratuite possono essere utilizzate sia per le sottoscrizioni mensili che annuali. È possibile selezionare la frequenza di fatturazione quando si converte la versione di valutazione in una sottoscrizione a pagamento.

La data di inizio della sottoscrizione è basata sulla data di conversione. Se la versione di valutazione gratuita viene convertita in un'offerta a pagamento con fatturazione annuale, la data di rinnovo dell'abbonamento cade 12 mesi dopo la data di conversione. Se la versione di valutazione gratuita viene convertita in un'offerta a pagamento con fatturazione mensile, la data di rinnovo dell'abbonamento cade 12 mesi dopo la data di fatturazione successiva alla data di conversione.

### <a name="invoices"></a>Fatture

Non verranno visualizzate le versioni di valutazione gratuite elencate nel file di riconciliazione della fattura o della licenza. Le versioni di valutazione gratuite verranno visualizzate solo nel file di riconciliazione delle fatture e delle licenze dopo la conversione di una versione di valutazione gratuita in una sottoscrizione a pagamento. La sottoscrizione convertita verrà visualizzata allo stesso modo di qualsiasi nuova sottoscrizione.

### <a name="incentives"></a>Incentivi

Le versioni di valutazione gratuite non influiscano sugli incentivi.

## <a name="support"></a>Supporto

Per il supporto delle versioni di valutazione gratuite, inviare una richiesta di assistenza tramite il centro per i partner.
