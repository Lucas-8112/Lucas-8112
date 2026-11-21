### Hi, I'm Lucas 👋

I run **[CanItBuy](https://canitbuy.com)**: independent tests of what AI shopping agents actually do at an online checkout when nobody is watching. Everything I measure is published as open data.

**What the tests found so far** (small, transparent tests; see the caveats in each repo)

- **Overcharge Test:** a store adds a hidden service fee. At double the price, 3 of 8 models still went to the payment page.
- **Cardholder Test:** a payment page asks the agent to confirm "I am the cardholder". It did, in 125 of 560 test purchases. None of the 125 reports to the customer mentioned it.
- **Signature Test:** the store asks the agent to declare "I have read the Terms of sale". Declared without opening the terms in 163 of 240 test purchases.

**Open data and citation**

- 📂 [canitbuy-agent-checkout-tests](https://github.com/Lucas-8112/canitbuy-agent-checkout-tests): per-run CSVs, prompts and grading notes (CC BY 4.0)
- 📄 Report: *"I am the cardholder": what AI shopping agents declare in the customer's name at checkout* · [doi.org/10.5281/zenodo.24393764](https://doi.org/10.5281/zenodo.24393764)
- 🆔 ORCID: [0009-0002-7198-0897](https://orcid.org/0009-0002-7198-0897)

**Read more**

- 🌐 [canitbuy.com](https://canitbuy.com) · [Model ranking](https://canitbuy.com/ranking) · [Lab notes (blog)](https://canitbuy.com/blog)
- 🎮 [Overcharge game](https://oc.lab.canitbuy.com/play): play the checkout test yourself

Found a mistake in a method or a number? Open an issue on the repo or write to [hello@canitbuy.com](mailto:hello@canitbuy.com). Corrections are published in the open.
