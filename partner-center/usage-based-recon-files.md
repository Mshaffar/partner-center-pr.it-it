---
title: Usage-based reconciliation files | Partner Center
ms.topic: article
ms.date: 11/21/2019
description: Understand usage-based reconciliation files in Partner Center.
ms.assetid: ''
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 3cf0f20ed266fa5302264ef07092d47c050a9206
ms.sourcegitcommit: 1c3d3b95135e1daad5ba5585a090e84ab0b97594
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 11/22/2019
ms.locfileid: "74389779"
---
# <a name="usage-based-file-fields"></a><span data-ttu-id="05f44-103">Campi dei file in base all'uso</span><span class="sxs-lookup"><span data-stu-id="05f44-103">Usage-based file fields</span></span>

<span data-ttu-id="05f44-104">Si applica a:</span><span class="sxs-lookup"><span data-stu-id="05f44-104">Applies to:</span></span>

- <span data-ttu-id="05f44-105">Centro per i partner</span><span class="sxs-lookup"><span data-stu-id="05f44-105">Partner Center</span></span>
- <span data-ttu-id="05f44-106">Centro per i partner per Microsoft Cloud for US Government</span><span class="sxs-lookup"><span data-stu-id="05f44-106">Partner Center for Microsoft Cloud for US Government</span></span>

<span data-ttu-id="05f44-107">To reconcile your charges against a customer's usage, compare the **ResellerID**, **ResellerName**, and **ResellerBillableAccount** from the reconciliation file with the **Customer name** and **Subscription ID** from Partner Center.</span><span class="sxs-lookup"><span data-stu-id="05f44-107">To reconcile your charges against a customer's usage, compare the **ResellerID**, **ResellerName**, and **ResellerBillableAccount** from the reconciliation file with the **Customer name** and **Subscription ID** from Partner Center.</span></span>

## <a name="fields-in-usage-based-reconciliation-files"></a><span data-ttu-id="05f44-108">Fields in usage-based reconciliation files</span><span class="sxs-lookup"><span data-stu-id="05f44-108">Fields in usage-based reconciliation files</span></span>

<span data-ttu-id="05f44-109">I campi seguenti illustrano quali servizi sono stati usati e la tariffa.</span><span class="sxs-lookup"><span data-stu-id="05f44-109">The following fields explain which services were used and the rate.</span></span>

| <span data-ttu-id="05f44-110">Column</span><span class="sxs-lookup"><span data-stu-id="05f44-110">Column</span></span> | <span data-ttu-id="05f44-111">Descrizione</span><span class="sxs-lookup"><span data-stu-id="05f44-111">Description</span></span> | <span data-ttu-id="05f44-112">Sample value(s)</span><span class="sxs-lookup"><span data-stu-id="05f44-112">Sample value(s)</span></span> |
| ------ | ----------- | ------------ |
| <span data-ttu-id="05f44-113">PartnerID</span><span class="sxs-lookup"><span data-stu-id="05f44-113">PartnerID</span></span> | <span data-ttu-id="05f44-114">Partner identifier, in GUID format.</span><span class="sxs-lookup"><span data-stu-id="05f44-114">Partner identifier, in GUID format.</span></span> | <span data-ttu-id="05f44-115">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span><span class="sxs-lookup"><span data-stu-id="05f44-115">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span></span> |
| <span data-ttu-id="05f44-116">PartnerName</span><span class="sxs-lookup"><span data-stu-id="05f44-116">PartnerName</span></span> | <span data-ttu-id="05f44-117">Partner name.</span><span class="sxs-lookup"><span data-stu-id="05f44-117">Partner name.</span></span> | <span data-ttu-id="05f44-118">*Contoso, Ltd.*</span><span class="sxs-lookup"><span data-stu-id="05f44-118">*Contoso, Ltd.*</span></span> |
| <span data-ttu-id="05f44-119">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="05f44-119">PartnerBillableAccountID</span></span> | <span data-ttu-id="05f44-120">Partner account identifier.</span><span class="sxs-lookup"><span data-stu-id="05f44-120">Partner account identifier.</span></span> | <span data-ttu-id="05f44-121">*1010578050*</span><span class="sxs-lookup"><span data-stu-id="05f44-121">*1010578050*</span></span> |
| <span data-ttu-id="05f44-122">CustomerName</span><span class="sxs-lookup"><span data-stu-id="05f44-122">CustomerName</span></span> | <span data-ttu-id="05f44-123">Customer's organization name, as reported in Partner Center.</span><span class="sxs-lookup"><span data-stu-id="05f44-123">Customer's organization name, as reported in Partner Center.</span></span> <span data-ttu-id="05f44-124">*Very important for reconciling the invoice with your system information.*</span><span class="sxs-lookup"><span data-stu-id="05f44-124">*Very important for reconciling the invoice with your system information.*</span></span> | <span data-ttu-id="05f44-125">*Test customer*</span><span class="sxs-lookup"><span data-stu-id="05f44-125">*Test customer*</span></span> |
| <span data-ttu-id="05f44-126">MPNID</span><span class="sxs-lookup"><span data-stu-id="05f44-126">MPNID</span></span> | <span data-ttu-id="05f44-127">MPN identifier of the CSP partner.</span><span class="sxs-lookup"><span data-stu-id="05f44-127">MPN identifier of the CSP partner.</span></span> | <span data-ttu-id="05f44-128">*4390934*</span><span class="sxs-lookup"><span data-stu-id="05f44-128">*4390934*</span></span> |
| <span data-ttu-id="05f44-129">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="05f44-129">ResellerMPNID</span></span> | <span data-ttu-id="05f44-130">MPN identifier of the reseller of record for the subscription.</span><span class="sxs-lookup"><span data-stu-id="05f44-130">MPN identifier of the reseller of record for the subscription.</span></span> <span data-ttu-id="05f44-131">For more information, see [how to itemize by partner](use-the-reconciliation-files.md#itemize-reconciliation-files-by-partner).</span><span class="sxs-lookup"><span data-stu-id="05f44-131">For more information, see [how to itemize by partner](use-the-reconciliation-files.md#itemize-reconciliation-files-by-partner).</span></span> | <span data-ttu-id="05f44-132">*4390934*</span><span class="sxs-lookup"><span data-stu-id="05f44-132">*4390934*</span></span> |
| <span data-ttu-id="05f44-133">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="05f44-133">InvoiceNumber</span></span> | <span data-ttu-id="05f44-134">Numero di fattura in cui viene visualizzata la transazione specificata.</span><span class="sxs-lookup"><span data-stu-id="05f44-134">Invoice number where the specified transaction appears.</span></span> | <span data-ttu-id="05f44-135">*D020001IVK*</span><span class="sxs-lookup"><span data-stu-id="05f44-135">*D020001IVK*</span></span> |
| <span data-ttu-id="05f44-136">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="05f44-136">ChargeStartDate</span></span> | <span data-ttu-id="05f44-137">Start date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span><span class="sxs-lookup"><span data-stu-id="05f44-137">Start date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="05f44-138">L'ora indicata è sempre l'inizio della giornata, le 0:00.</span><span class="sxs-lookup"><span data-stu-id="05f44-138">The time is always the beginning of the day, 0:00.</span></span> | <span data-ttu-id="05f44-139">*2/1/2019 0:00*</span><span class="sxs-lookup"><span data-stu-id="05f44-139">*2/1/2019 0:00*</span></span> |
| <span data-ttu-id="05f44-140">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="05f44-140">ChargeEndDate</span></span> | <span data-ttu-id="05f44-141">End date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span><span class="sxs-lookup"><span data-stu-id="05f44-141">End date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="05f44-142">L'ora indicata è sempre la fine della giornata, le 23:59.</span><span class="sxs-lookup"><span data-stu-id="05f44-142">The time is always the end of the day, 23:59.</span></span> | <span data-ttu-id="05f44-143">*2/28/2019 23:59*</span><span class="sxs-lookup"><span data-stu-id="05f44-143">*2/28/2019 23:59*</span></span> |
| <span data-ttu-id="05f44-144">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="05f44-144">SubscriptionID</span></span> | <span data-ttu-id="05f44-145">Identificatore univoco di una sottoscrizione nella piattaforma di fatturazione Microsoft.</span><span class="sxs-lookup"><span data-stu-id="05f44-145">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="05f44-146">May be useful to identify the subscription when contacting support.</span><span class="sxs-lookup"><span data-stu-id="05f44-146">May be useful to identify the subscription when contacting support.</span></span> <span data-ttu-id="05f44-147">Not used for reconciliation.</span><span class="sxs-lookup"><span data-stu-id="05f44-147">Not used for reconciliation.</span></span> <span data-ttu-id="05f44-148">*This is not the same as the **Subscription ID** on the Partner Admin Console.*</span><span class="sxs-lookup"><span data-stu-id="05f44-148">*This is not the same as the **Subscription ID** on the Partner Admin Console.*</span></span> | <span data-ttu-id="05f44-149">*usCBMgAAAAAAAAIA*</span><span class="sxs-lookup"><span data-stu-id="05f44-149">*usCBMgAAAAAAAAIA*</span></span> |
| <span data-ttu-id="05f44-150">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="05f44-150">SubscriptionName</span></span> | <span data-ttu-id="05f44-151">Nickname for the service offering.</span><span class="sxs-lookup"><span data-stu-id="05f44-151">Nickname for the service offering.</span></span> | <span data-ttu-id="05f44-152">*Microsoft Azure*</span><span class="sxs-lookup"><span data-stu-id="05f44-152">*Microsoft Azure*</span></span> |
| <span data-ttu-id="05f44-153">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="05f44-153">SubscriptionDescription</span></span> | <span data-ttu-id="05f44-154">Line of business of the service offering.</span><span class="sxs-lookup"><span data-stu-id="05f44-154">Line of business of the service offering.</span></span> | <span data-ttu-id="05f44-155">*Microsoft Azure*</span><span class="sxs-lookup"><span data-stu-id="05f44-155">*Microsoft Azure*</span></span> |
| <span data-ttu-id="05f44-156">OrderID</span><span class="sxs-lookup"><span data-stu-id="05f44-156">OrderID</span></span> | <span data-ttu-id="05f44-157">Identificatore univoco di un ordine nella piattaforma di fatturazione Microsoft.</span><span class="sxs-lookup"><span data-stu-id="05f44-157">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="05f44-158">May be useful to identify the subscription when contacting support.</span><span class="sxs-lookup"><span data-stu-id="05f44-158">May be useful to identify the subscription when contacting support.</span></span> <span data-ttu-id="05f44-159">Not used for reconciliation.</span><span class="sxs-lookup"><span data-stu-id="05f44-159">Not used for reconciliation.</span></span> | <span data-ttu-id="05f44-160">*566890604832738111*</span><span class="sxs-lookup"><span data-stu-id="05f44-160">*566890604832738111*</span></span> |
| <span data-ttu-id="05f44-161">ServiceName</span><span class="sxs-lookup"><span data-stu-id="05f44-161">ServiceName</span></span> | <span data-ttu-id="05f44-162">Nome del servizio di Azure in questione.</span><span class="sxs-lookup"><span data-stu-id="05f44-162">The name of the Azure service in question.</span></span> | <span data-ttu-id="05f44-163">*VIRTUAL MACHINES*</span><span class="sxs-lookup"><span data-stu-id="05f44-163">*VIRTUAL MACHINES*</span></span> |
| <span data-ttu-id="05f44-164">ServiceType</span><span class="sxs-lookup"><span data-stu-id="05f44-164">ServiceType</span></span> | <span data-ttu-id="05f44-165">The specific type of Azure service.</span><span class="sxs-lookup"><span data-stu-id="05f44-165">The specific type of Azure service.</span></span> | <span data-ttu-id="05f44-166">*Service Bus – Individual or Pack*, *SQL Azure database – Business or Web Edition*</span><span class="sxs-lookup"><span data-stu-id="05f44-166">*Service Bus – Individual or Pack*, *SQL Azure database – Business or Web Edition*</span></span> |
| <span data-ttu-id="05f44-167">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="05f44-167">ResourceGUID</span></span> | <span data-ttu-id="05f44-168">Identificatore univoco specifico per l'intera struttura di prezzi e dati di servizio.</span><span class="sxs-lookup"><span data-stu-id="05f44-168">Specific unique identifier for all the service data and pricing structure.</span></span> | <span data-ttu-id="05f44-169">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span><span class="sxs-lookup"><span data-stu-id="05f44-169">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span></span> |
| <span data-ttu-id="05f44-170">NomeRisorsa</span><span class="sxs-lookup"><span data-stu-id="05f44-170">ResourceName</span></span> | <span data-ttu-id="05f44-171">Nome della risorsa Azure.</span><span class="sxs-lookup"><span data-stu-id="05f44-171">The name of the Azure resource.</span></span> | <span data-ttu-id="05f44-172">*Data Transfer In (GB)* , *Data Transfer Out (GB)*</span><span class="sxs-lookup"><span data-stu-id="05f44-172">*Data Transfer In (GB)*, *Data Transfer Out (GB)*</span></span> |
| <span data-ttu-id="05f44-173">Area geografica</span><span class="sxs-lookup"><span data-stu-id="05f44-173">Region</span></span> | <span data-ttu-id="05f44-174">The region to which the usage applies.</span><span class="sxs-lookup"><span data-stu-id="05f44-174">The region to which the usage applies.</span></span> <span data-ttu-id="05f44-175">Primarily used to assign rates to data transfers, because rates vary by region.</span><span class="sxs-lookup"><span data-stu-id="05f44-175">Primarily used to assign rates to data transfers, because rates vary by region.</span></span> | <span data-ttu-id="05f44-176">*Asia Pacific*, *Europe*, *Latin America*, *North America*</span><span class="sxs-lookup"><span data-stu-id="05f44-176">*Asia Pacific*, *Europe*, *Latin America*, *North America*</span></span> |
| <span data-ttu-id="05f44-177">SKU</span><span class="sxs-lookup"><span data-stu-id="05f44-177">SKU</span></span> | <span data-ttu-id="05f44-178">Unique Microsoft identifier for an offer.</span><span class="sxs-lookup"><span data-stu-id="05f44-178">Unique Microsoft identifier for an offer.</span></span> | <span data-ttu-id="05f44-179">*7UD-00001*</span><span class="sxs-lookup"><span data-stu-id="05f44-179">*7UD-00001*</span></span> |
| <span data-ttu-id="05f44-180">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="05f44-180">DetailLineItemId</span></span> | <span data-ttu-id="05f44-181">An identifier and quantity to itemize different rates for a service or resource in a given billing period.</span><span class="sxs-lookup"><span data-stu-id="05f44-181">An identifier and quantity to itemize different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="05f44-182">For Azure tiered pricing, there may be one rate for up to a certain quantity of billable units, then a different rate after that quantity.</span><span class="sxs-lookup"><span data-stu-id="05f44-182">For Azure tiered pricing, there may be one rate for up to a certain quantity of billable units, then a different rate after that quantity.</span></span> | <span data-ttu-id="05f44-183">*1*</span><span class="sxs-lookup"><span data-stu-id="05f44-183">*1*</span></span> |
| <span data-ttu-id="05f44-184">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="05f44-184">ConsumedQuantity</span></span> | <span data-ttu-id="05f44-185">The amount of service consumed (such as hours or GB) during the reporting period.</span><span class="sxs-lookup"><span data-stu-id="05f44-185">The amount of service consumed (such as hours or GB) during the reporting period.</span></span> <span data-ttu-id="05f44-186">Include anche gli utilizzi non fatturati relativi a periodi di reporting precedenti.</span><span class="sxs-lookup"><span data-stu-id="05f44-186">Also includes any unbilled usage from previous reporting periods.</span></span> | <span data-ttu-id="05f44-187">*11*</span><span class="sxs-lookup"><span data-stu-id="05f44-187">*11*</span></span> |
| <span data-ttu-id="05f44-188">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="05f44-188">IncludedQuantity</span></span> | <span data-ttu-id="05f44-189">Unità incluse nell'ambito dell'offerta.</span><span class="sxs-lookup"><span data-stu-id="05f44-189">Units included as part of the offer.</span></span> <span data-ttu-id="05f44-190">Typically not present in CSP.</span><span class="sxs-lookup"><span data-stu-id="05f44-190">Typically not present in CSP.</span></span> | <span data-ttu-id="05f44-191">*0*</span><span class="sxs-lookup"><span data-stu-id="05f44-191">*0*</span></span> |
| <span data-ttu-id="05f44-192">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="05f44-192">OverageQuantity</span></span> | <span data-ttu-id="05f44-193">Units not included as part of the offer.</span><span class="sxs-lookup"><span data-stu-id="05f44-193">Units not included as part of the offer.</span></span> <span data-ttu-id="05f44-194">These must be paid for by the partner.</span><span class="sxs-lookup"><span data-stu-id="05f44-194">These must be paid for by the partner.</span></span> <span data-ttu-id="05f44-195">Equal to **ConsumedQuantity** minus **IncludedQuantity**.</span><span class="sxs-lookup"><span data-stu-id="05f44-195">Equal to **ConsumedQuantity** minus **IncludedQuantity**.</span></span> | <span data-ttu-id="05f44-196">*11*</span><span class="sxs-lookup"><span data-stu-id="05f44-196">*11*</span></span> |
| <span data-ttu-id="05f44-197">ListPrice</span><span class="sxs-lookup"><span data-stu-id="05f44-197">ListPrice</span></span> | <span data-ttu-id="05f44-198">Offer price in effect at subscription's start date.</span><span class="sxs-lookup"><span data-stu-id="05f44-198">Offer price in effect at subscription's start date.</span></span> | <span data-ttu-id="05f44-199">*$0.0808*</span><span class="sxs-lookup"><span data-stu-id="05f44-199">*$0.0808*</span></span> |
| <span data-ttu-id="05f44-200">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="05f44-200">PretaxCharges</span></span> | <span data-ttu-id="05f44-201">Equal to **ListPrist** multiplied by **OverageQuantity**, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="05f44-201">Equal to **ListPrist** multiplied by **OverageQuantity**, rounded to the nearest cent.</span></span> | <span data-ttu-id="05f44-202">*$0.085*</span><span class="sxs-lookup"><span data-stu-id="05f44-202">*$0.085*</span></span> |
| <span data-ttu-id="05f44-203">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="05f44-203">TaxAmount</span></span> | <span data-ttu-id="05f44-204">Tax amount charged.</span><span class="sxs-lookup"><span data-stu-id="05f44-204">Tax amount charged.</span></span> <span data-ttu-id="05f44-205">Based on your market's tax rules and specific circumstances.</span><span class="sxs-lookup"><span data-stu-id="05f44-205">Based on your market's tax rules and specific circumstances.</span></span> | <span data-ttu-id="05f44-206">*$0.08*</span><span class="sxs-lookup"><span data-stu-id="05f44-206">*$0.08*</span></span> |
| <span data-ttu-id="05f44-207">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="05f44-207">PostTaxTotal</span></span> | <span data-ttu-id="05f44-208">Totale al netto delle imposte, se le imposte sono applicabili.</span><span class="sxs-lookup"><span data-stu-id="05f44-208">Total after tax, when tax is applicable.</span></span> | <span data-ttu-id="05f44-209">*$0.93*</span><span class="sxs-lookup"><span data-stu-id="05f44-209">*$0.93*</span></span> |
| <span data-ttu-id="05f44-210">Currency</span><span class="sxs-lookup"><span data-stu-id="05f44-210">Currency</span></span> | <span data-ttu-id="05f44-211">Tipo di valuta.</span><span class="sxs-lookup"><span data-stu-id="05f44-211">Currency type.</span></span> <span data-ttu-id="05f44-212">Ogni entità di fatturazione ha una sola valuta.</span><span class="sxs-lookup"><span data-stu-id="05f44-212">Each billing entity has only one currency.</span></span> <span data-ttu-id="05f44-213">Check that it matches your first invoice and then after any major billing platform updates.</span><span class="sxs-lookup"><span data-stu-id="05f44-213">Check that it matches your first invoice and then after any major billing platform updates.</span></span> | <span data-ttu-id="05f44-214">*EUR*</span><span class="sxs-lookup"><span data-stu-id="05f44-214">*EUR*</span></span> |
| <span data-ttu-id="05f44-215">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="05f44-215">PretaxEffectiveRate</span></span> | <span data-ttu-id="05f44-216">Prezzo unitario prima dell'applicazione delle imposte.</span><span class="sxs-lookup"><span data-stu-id="05f44-216">Pretax price per unit.</span></span> <span data-ttu-id="05f44-217">Equal to **PretaxCharges** divided by **OverageQuantity**, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="05f44-217">Equal to **PretaxCharges** divided by **OverageQuantity**, rounded to the nearest cent.</span></span> | <span data-ttu-id="05f44-218">*$0.08*</span><span class="sxs-lookup"><span data-stu-id="05f44-218">*$0.08*</span></span> |
| <span data-ttu-id="05f44-219">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="05f44-219">PostTaxEffectiveRate</span></span> | <span data-ttu-id="05f44-220">Prezzo unitario dopo l'applicazione delle imposte.</span><span class="sxs-lookup"><span data-stu-id="05f44-220">Post tax price per unit.</span></span> <span data-ttu-id="05f44-221">Equal to **PostTaxTotal** divided by **OverageQuantity**, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="05f44-221">Equal to **PostTaxTotal** divided by **OverageQuantity**, rounded to the nearest cent.</span></span> <span data-ttu-id="05f44-222">Or, equal to **PretaxEffectiveRate** plus thet tax rate per unit amoun, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="05f44-222">Or, equal to **PretaxEffectiveRate** plus thet tax rate per unit amoun, rounded to the nearest cent.</span></span> | <span data-ttu-id="05f44-223">*$0.08*</span><span class="sxs-lookup"><span data-stu-id="05f44-223">*$0.08*</span></span> |
| <span data-ttu-id="05f44-224">ChargeType</span><span class="sxs-lookup"><span data-stu-id="05f44-224">ChargeType</span></span> | <span data-ttu-id="05f44-225">The [type of charge](recon-file-charge-types.md) or adjustment.</span><span class="sxs-lookup"><span data-stu-id="05f44-225">The [type of charge](recon-file-charge-types.md) or adjustment.</span></span> | <span data-ttu-id="05f44-226">See [charge types](recon-file-charge-types.md).</span><span class="sxs-lookup"><span data-stu-id="05f44-226">See [charge types](recon-file-charge-types.md).</span></span> |
| <span data-ttu-id="05f44-227">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="05f44-227">CustomerBillableAccount</span></span> | <span data-ttu-id="05f44-228">Unique account identifier in the Microsoft billing platform.</span><span class="sxs-lookup"><span data-stu-id="05f44-228">Unique account identifier in the Microsoft billing platform.</span></span> | <span data-ttu-id="05f44-229">*1280018095*</span><span class="sxs-lookup"><span data-stu-id="05f44-229">*1280018095*</span></span> |
| <span data-ttu-id="05f44-230">UsageDate</span><span class="sxs-lookup"><span data-stu-id="05f44-230">UsageDate</span></span> | <span data-ttu-id="05f44-231">Data di distribuzione del servizio.</span><span class="sxs-lookup"><span data-stu-id="05f44-231">Date of service deployment.</span></span> | <span data-ttu-id="05f44-232">*2/1/2019 0:00*</span><span class="sxs-lookup"><span data-stu-id="05f44-232">*2/1/2019 0:00*</span></span> |
| <span data-ttu-id="05f44-233">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="05f44-233">MeteredRegion</span></span> | <span data-ttu-id="05f44-234">Identifies the location of a data center within the region (for services where this value is applicable and populated).</span><span class="sxs-lookup"><span data-stu-id="05f44-234">Identifies the location of a data center within the region (for services where this value is applicable and populated).</span></span> | <span data-ttu-id="05f44-235">*East Asia*, *South East Asia*, *North Europe*, *West Europe*, *North Central US*, *South Central US*</span><span class="sxs-lookup"><span data-stu-id="05f44-235">*East Asia*, *South East Asia*, *North Europe*, *West Europe*, *North Central US*, *South Central US*</span></span> |
| <span data-ttu-id="05f44-236">MeteredService</span><span class="sxs-lookup"><span data-stu-id="05f44-236">MeteredService</span></span> | <span data-ttu-id="05f44-237">Identifies the individual Azure service usage when it's not specifically identified in the **ServiceName** column.</span><span class="sxs-lookup"><span data-stu-id="05f44-237">Identifies the individual Azure service usage when it's not specifically identified in the **ServiceName** column.</span></span> <span data-ttu-id="05f44-238">For example, data transfers are reported as *Microsoft Azure - All Services* in the **ServiceName** column.</span><span class="sxs-lookup"><span data-stu-id="05f44-238">For example, data transfers are reported as *Microsoft Azure - All Services* in the **ServiceName** column.</span></span> | <span data-ttu-id="05f44-239">*AccessControl*, *CDN*, *Compute*, *Database*, *ServiceBus*, *Storage*</span><span class="sxs-lookup"><span data-stu-id="05f44-239">*AccessControl*, *CDN*, *Compute*, *Database*, *ServiceBus*, *Storage*</span></span> |
| <span data-ttu-id="05f44-240">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="05f44-240">MeteredServiceType</span></span> | <span data-ttu-id="05f44-241">Subheading for **MeteredService** field that provides additional clarification of Azure service usage.</span><span class="sxs-lookup"><span data-stu-id="05f44-241">Subheading for **MeteredService** field that provides additional clarification of Azure service usage.</span></span> | <span data-ttu-id="05f44-242">*EXTERNAL*</span><span class="sxs-lookup"><span data-stu-id="05f44-242">*EXTERNAL*</span></span> |
| <span data-ttu-id="05f44-243">Project</span><span class="sxs-lookup"><span data-stu-id="05f44-243">Project</span></span> | <span data-ttu-id="05f44-244">Customer-defined name for their service instance.</span><span class="sxs-lookup"><span data-stu-id="05f44-244">Customer-defined name for their service instance.</span></span> | <span data-ttu-id="05f44-245">*ORDDC52E52FDEF405786F0642DD0108BE4*</span><span class="sxs-lookup"><span data-stu-id="05f44-245">*ORDDC52E52FDEF405786F0642DD0108BE4*</span></span> |
| <span data-ttu-id="05f44-246">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="05f44-246">ServiceInfo</span></span> | <span data-ttu-id="05f44-247">The number of Azure Service Bus connections that were provisioned and utilized on a given day.</span><span class="sxs-lookup"><span data-stu-id="05f44-247">The number of Azure Service Bus connections that were provisioned and utilized on a given day.</span></span> | <span data-ttu-id="05f44-248">*1.000000 Connections / 30 days* (if you had an individually provisioned connection during a 30-day month), *25 Connections / 30 Days – Used: 1.000000* (if you had a 25 pack of Service Bus connections provisioned and you utilized 1 during that day)</span><span class="sxs-lookup"><span data-stu-id="05f44-248">*1.000000 Connections / 30 days* (if you had an individually provisioned connection during a 30-day month), *25 Connections / 30 Days – Used: 1.000000* (if you had a 25 pack of Service Bus connections provisioned and you utilized 1 during that day)</span></span> |
| <span data-ttu-id="05f44-249">CustomerID</span><span class="sxs-lookup"><span data-stu-id="05f44-249">CustomerID</span></span> | <span data-ttu-id="05f44-250">Unique Microsoft identifier for the customer, in GUID format.</span><span class="sxs-lookup"><span data-stu-id="05f44-250">Unique Microsoft identifier for the customer, in GUID format.</span></span> | <span data-ttu-id="05f44-251">*ORDDC52E52FDEF405786F0642DD0108BE4*</span><span class="sxs-lookup"><span data-stu-id="05f44-251">*ORDDC52E52FDEF405786F0642DD0108BE4*</span></span> |
| <span data-ttu-id="05f44-252">DomainName</span><span class="sxs-lookup"><span data-stu-id="05f44-252">DomainName</span></span> | <span data-ttu-id="05f44-253">Customer's domain name.</span><span class="sxs-lookup"><span data-stu-id="05f44-253">Customer's domain name.</span></span> <span data-ttu-id="05f44-254">Questo campo potrebbe risultare vuoto fino al secondo ciclo di fatturazione.</span><span class="sxs-lookup"><span data-stu-id="05f44-254">This field may appear blank until the second billing cycle.</span></span> | <span data-ttu-id="05f44-255">*example.onmicrosoft.com*</span><span class="sxs-lookup"><span data-stu-id="05f44-255">*example.onmicrosoft.com*</span></span> |
| <span data-ttu-id="05f44-256">Unit</span><span class="sxs-lookup"><span data-stu-id="05f44-256">Unit</span></span> | <span data-ttu-id="05f44-257">The unit of the resource **Name**.</span><span class="sxs-lookup"><span data-stu-id="05f44-257">The unit of the resource **Name**.</span></span> | <span data-ttu-id="05f44-258">*GB* or *HOURS*</span><span class="sxs-lookup"><span data-stu-id="05f44-258">*GB* or *HOURS*</span></span> |