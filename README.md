# SCM Assistant

## Public Chatbot URL
https://cloud.flowiseai.com/chatbot/2fb805b4-a67c-4b84-b4ca-27b7a5ca296b

---

## Models Used

### LLM
Groq - llama-3.3-70b-versatile

### Embeddings
Mistral Embed

---

## Chunk Configurations Tested

### Config 1
- Chunk Size: 1000
- Chunk Overlap: 100

Result:
Good balance between accuracy and response speed.

### Config 2
- Chunk Size: 500
- Chunk Overlap: 50

Result:
More detailed retrieval but slightly fragmented answers.

---

## Sample Questions & Answers

### Q1: Tier-3 suppliers with active disruption flag
For Tier-3 suppliers with an active disruption flag, according to the provided context, they would fall under the Level 3 — Activate response tier, which 
requires immediate escalation to the CPO, activation of an alternate supplier for a minimum of 40% of the volume within 10 business days, and a safety stock 
adjustment of +50%. Additionally, a full Root Cause Analysis (RCA) is required within 15 business days.

### Q2: Supplier Watch List suppliers
Suppliers with a Compliance Score below 60 at any audit are placed on the Supplier Watch List (SWL) status. When a supplier is on SWL status, new PO issuance 
is limited to 20% of the prior quarter's volume.


### Q3: Highest total PO value region
No single region may account for more than 45% of total annual procurement spend. However, the region with the highest total PO value is not explicitly stated, 
but it is limited to a maximum of 45% of the total annual procurement spend.


---

## Improvements I Would Make

- Add memory support
- Add hybrid search
- Add reranking
- Add dashboard analytics
- Add multilingual support
- Use persistent vector database
