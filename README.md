# Reviews

## Introduction

My reviews of stuff.

## Reviews

### Stem Cell Discovery Engine

http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3245064/

Shannan Ho Sui's overview of the Stem Cell Discover Engine a
platform for reliably collected curated (biological) datasets
and running analyses on them using an associated Galaxy
instance. Curation is a significant aspect of the system.
Metadata exchange, important for provenance and stuff, is done
via ISA-Tab format.

### Open Source and Open Data Should Be Standard Practices

DOI: 10.1021/acs.jpclett.5b00285

Gezelter writes a, by now familiar, plea calling for more open
source support in sciences. Particularly chemistry.

It seems innocuous, but got a somewhat "pile-on" response from
Kyrlov et al (see below). The SSI had a whole series of blog
articles about it.

### What Is the Price of Open-Source Software?

On the face of it 10 authors pile on to Gezelter (see above) and
rebutt his "open source" position. From the perspective of
someone like me, the reading is hard. There are nuggets of
interest and nourishment there, but you have to wade through a
lot of rant which boils down to "we want to sell software".

Note that the 10 authors are all invested in various proprietary
(and very much for sale) chemical software packages. So they
have a vested interest.

See also a rebuttal by SSI (blog) and a rebuttal to the response
by Herbert (corresponding author).

Anna I. Krylov Q
John M. Herbert Q
Filipp Furche T
Martin Head-Gordon Q
Peter J. Knowles M
Roland Lindh m
Frederick R. Manby M
Peter Pulay P
Chris-Kriton Skylaris O
Hans-Joachim Werner M

Q Q-Chem
P PQS, Inc (actually, Parallel Quantum Solutions)
FF Turbomole
M Molpro
m Molcas
O Onetep

## Open source tools for large-scale neuroscience

http://thefreemanlab.com/work/papers/freeman-2015-current-opinion.pdf

http://www.sciencedirect.com/science/article/pii/S0959438815000756

doi:10.1016/j.conb.2015.04.002

In some sense, this is the by now familar story. Better cheaper devices
giving more data. Cost per byte going down and down (light field
zebrafish brain 1TB. Lots of analysis needed. Existing analysis
approach is ad hoc. Standardisation required. Need to go from
single workstation to highly parallel.

Take a swing at proprietary tools before laying out the "Open
Source" vision:

"
fast open-source libraries for common analyses, available to
anyone and developed by all, with intuitive, modular code bases
supporting customization, comparison, and benchmarking of
pipelines and parameters, implemented in distributed systems
that can run in cloud computing environments, with web-based
interfaces for interactively exploring data and visualizing
results.
"

Google MapReduce, Yahoo Hadoop, Apache Spark. Python, R, Julia,
iPython.

And then a big rant against Matlab: "it is hard to recommend as
a primary analysis tool in a future of open and collaborative
science"

Brief overview of visualisations, and then a wish for creating
interactive "apps" (my term) instead of visualisations. Such as
can be achieved with the interactive notebook. iPython.

Following the Summary is a sort of map of the future which is
well worth reading. Data formats, benchmarking, valuing
contributions, unifying local and distributed computing, GPUs,
streaming.

Extensive review bibiliography.

Opinion: Quite a nice article, any one section of which could
well be expanded into a larger discussion. Discussions of data
formats and benchmarking could be linked to wardley's
value chain mapping (See
http://blog.gardeviance.org/2015/02/an-introduction-to-wardley-value-chain.html
for example).
