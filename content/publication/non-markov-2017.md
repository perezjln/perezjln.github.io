+++
title = "Non-Markovian control using gated end-to-end memory policy networks"
#date  = "2017-05-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Julien Perez", "Tomi Silander"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "CoRR, Vol. abs/1705.10993, 2017"
#publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "Partially observable environments present an important open challenge in the domain of sequential control learning with delayed rewards. Despite numerous attempts during the two last decades, the majority of reinforcement learning algorithms and associated approximate models, applied to this context, still assume Markovian state transitions. In this paper, we explore the use of a recently proposed attention-based model, the Gated End-to-End Memory Network, for sequential control. We call the resulting model the Gated End-to-End Memory Policy Network. More precisely, we use a model-free value-based algorithm to learn policies for partially observed domains using this memory-enhanced neural network. This model is end-to-end learnable and it features unbounded memory. Indeed, because of its attention mechanism and associated non-parametric memory, the proposed model allows us to define an attention mechanism over the observation stream unlike recurrent models. We show encouraging results that illustrate the capability of our attention-based model in the context of the continuous-state non-stationary control problem of stock trading. We also present an OpenAI Gym environment for simulated stock exchange and explain its relevance as a benchmark for the field of non-Markovian decision process learning."


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://arxiv.org/abs/1705.10993"
url_preprint = "https://arxiv.org/abs/1705.10993"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.