# Summary of feedbacks 

01/06/2024

### General Recommendations

1. **In-depth Analysis of Bitcoin and Script Language:**
   - Provide a comprehensive analysis of Bitcoin, focusing on the content of blocks and the Bitcoin Script domain-specific language. 
   - Discuss its limitations and how it can be "hacked" to include data not initially intended for such purposes.

2. **Use of Examples and Clear Explanations:**
   - Incorporate clear examples and explanatory material.
   - Do not assume the reader is an expert in Bitcoin jargon.
   - Critically analyze blockchain-related claims and the technical contributions and limitations of the projects discussed.

3. **Exploration of Layer-2 Solutions:**
   - Thoroughly review scientific literature on layer-2 solutions, not just those specific to Bitcoin.
   - Critically evaluate the possibilities and limitations of layer-2 support in Bitcoin and other blockchains.

4. **Language and Presentation:**
   - Ensure the entire document is in a single language, preferably English.
   - Focus on proper citations and avoid using copy-pasted screenshots and illustrations from the web.

### Detailed Feedback

#### Analysis of "Envelop" and Related Concepts

- **Envelop Hack:**
  - Explain that the "envelop" is a method to include arbitrary data in Bitcoin blocks using the Bitcoin stack language. 
  - Highlight that miners ignore the evaluation of the envelope and any included commands, leading to an empty stack and transaction validation despite the additional data.
  - Mention that external mechanisms can interpret the piggybacked data according to external semantics.

- **OP_RETURN and STAMPS:**
  - Critique `OP_RETURN` and STAMPS, particularly regarding the impracticality of storing images on the main Bitcoin ledger due to high costs.
  - Include a critical analysis of the limitations of these mechanisms.

- **Pedagogical Examples:**
  - Provide clear, pedagogical examples of how to include binary/blob data in the Bitcoin ledger.
  - Discuss possible use cases for such data inclusion.

#### Section 2 Feedback

- **Clarifications and Focus:**
  - Clarify the use of CBOR vs. BLOB implementation and the role of Atomicals in registering arbitrary binary data.
  - The way L2 systems encode data in a blob is irrelevant from Bitcoin's perspective.
  - Avoid irrelevant discussions, such as those on relational databases, unless directly pertinent to the topic.

- **Misunderstandings:**
  - Correct any misunderstandings about Ethereum's use of blob formats and machine state evolution.
  - Clarify that blobs in Bitcoin are binary objects whose structure is unknown to handlers (miners), unlike Ethereum L2 protocols.

- **Presentation Improvements:**
  - Use consistent presentation formats for figures and avoid bitmaps for listings.
  - Provide a simple example abstracting the marketing language used by proposers of Atomicals or similar protocols.

#### Section 3 Feedback

- **Execution of Code in BLOBs:**
  - Discuss whether code contained in BLOBs can be executed, particularly in the context of L2 solutions like Ethereum's rollups.
  - Explain why L1 miners cannot verify such code on Bitcoin and the implications for L2 solutions.

- **Comparison with Other UTXOs:**
  - Explore how other UTXOs, like Cardano, address similar challenges.
  - Study their approaches to L2 solutions and compare them with Bitcoin's capabilities.

### Summary and Structural Improvements

- **Preliminary and Drafty Content:**
  - Acknowledge that the work is preliminary and drafty in its current state.
  - Emphasize the need for a structured and well-presented document.

- **Self-contained Document:**
  - Ensure the document is self-contained and comprehensible to readers unfamiliar with specific concepts or jargon.
  - Avoid infatuated claims and use clear, pedagogical examples.

- **Refining Objectives:**
  - Clarify the specific goals of your analysis of L2 protocols anchoring data on Bitcoin L1.
  - Define whether the aim is to establish a common framework, propose a new L2 solution, or address a specific problem.

- **Literature Coverage:**
  - Conduct an extensive review of the literature on Bitcoin/blockchain and layer-2 solutions.
  - Start with foundational papers and well-cited SoK papers, such as those by Sguanci et al. (2021), Jourenko et al. (2019), and others listed in the feedback.

- **Correct Citations:**
  - Ensure all scientific works are correctly cited using Google Scholar-provided bibtex entries.
  - For example, the citation for Rohrer et al. (2019) should be correctly formatted as provided.