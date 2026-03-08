# oddbiology

See also https://github.com/cmdcolin/oddgenes

This repo covers weird biology in general — things that don't entirely fit into
oddgenes (which focuses on gene annotations and bioinformatics assumptions).

Please feel free to make PRs for more stuff!

## Non-random segregation of chromosomes

Normally we assume each chromosome has a 50/50 chance of ending up in either
daughter cell. Non-random segregation means some chromosomes "cheat" — they are
preferentially passed to certain cells, spreading through a population faster
than expected.

https://en.wikipedia.org/wiki/Non-random_segregation_of_chromosomes

Examples:

- **Aphids**: the X chromosome consistently moves to the larger daughter cell
  during spermatogenesis, ensuring all offspring are female
- **Butterflies (ZZ/Z0 type, e.g. Taleporia tubulosa)**: Z chromosome
  segregation is influenced by temperature and maternal age
- **Butterflies (ZZ/ZW type)**: the W chromosome always enters the egg cell,
  resulting exclusively in female offspring
- **Flowering plants (e.g. maize K10 chromosome)**: K10 is an abnormal version
  of chromosome 10 that cheats during meiosis — it hijacks the cell division
  machinery so it ends up in the egg cell ~70% of the time instead of 50%
- **Scale insects**: males are parahaploid — they have both parents'
  chromosomes, but only the mother's are switched on and passed to offspring
- **B chromosomes in plants (e.g. Lilium callosum)**: B chromosomes are extra
  "selfish" chromosomes with no known function that accumulate across
  generations by biasing their own transmission

This is closely related to meiotic drive / gene drive, where selfish genetic
elements bias their own transmission. Engineered gene drives (e.g. using CRISPR)
exploit this principle to spread genes through wild populations.

https://en.wikipedia.org/wiki/Intragenomic_conflict#Segregation_distortion
https://en.wikipedia.org/wiki/Gene_drive

## Inheritance without DNA

### Prions

Prions are heritable elements based on protein shape, not DNA. A misfolded
protein can force other copies of itself to misfold too — causing brain-wasting
diseases like mad cow disease and scrapie in mammals. In yeast, prions like
[PSI+] and [URE3] are genuinely inherited across generations through cell
division, altering traits with no DNA change involved.

https://en.wikipedia.org/wiki/Prion
https://en.wikipedia.org/wiki/Yeast_prion

### Transgenerational epigenetic inheritance

Chemical modifications on top of DNA can be passed down across generations
without changing the DNA sequence itself. The idea that experiences like famine
can affect descendants garners much attention. Evidence exists in plants,
C. elegans, and some mammalian contexts, though the extent in humans remains
debated.

https://en.wikipedia.org/wiki/Transgenerational_epigenetic_inheritance

There are skeptics also
http://www.wiringthebrain.com/2018/07/calibrating-scientific-skepticism-wider.html

## Virus genes repurposed by animals

### Arc — a virus gene co-opted for neuron communication

Arc is a brain gene essential for memory that evolved from an ancient virus. Its
protein assembles into virus-like shells, packages its own RNA, and ships it
between neurons. In fruit flies, a related gene (dArc1) does the same thing —
your neurons are literally sending each other virus-like packages to communicate.

https://www.cell.com/cell/fulltext/S0092-8674(17)31504-0
https://www.cell.com/cell/fulltext/S0092-8674(17)31502-7

### Syncytins — retroviral genes essential for the placenta

Syncytins are genes required for building the placenta in mammals, and they come
from ancient retroviruses that infected our ancestors. Different mammalian
lineages independently captured different retroviruses for this purpose.

https://en.wikipedia.org/wiki/Syncytin

## Evolution

### Odd evolutionary relationships

Try our game https://phyloguessr.com to test your knowledge of these!

- Mangoes, cashews, and pistachio are related to poison ivy (https://www.scientificamerican.com/article/what-do-cashews-mangoes-and-poison-ivy-have-in-common/)
- Humans are more closely related to mushrooms than plants (https://gizmodo.com/why-are-mushrooms-more-like-humans-than-they-are-like-p-5940434)
- Humans are more closely related to a sea urchin than a fly or worm (https://www.abc.net.au/science/articles/2006/11/10/1785449.htm)
- Comb jellies are likely the sibling group to all other animals, not sponges (https://www.mbari.org/news/genetic-research-offers-new-perspective-on-the-early-evolution-of-animals/)
- Oak trees are more related to pumpkins than to pine trees (https://www.youtube.com/watch?v=ONVpFtiD-fo)
- Horses are more closely related to rhinos than antelope (even vs odd toed ungulates) (https://positivepeerpressure.blog/quirky-evolution-5-unlikely-animal-relatives-hiding-in-plain-sight-6e08cfd299a7)
- Hyraxes (rodent-looking mammals) are more related to manatees and elephants than to any rodent (https://en.wikipedia.org/wiki/Hyrax)
- "There is no such thing as a tree" (woody trees are not monophyletic) (https://eukaryotewritesblog.com/2021/05/02/theres-no-such-thing-as-a-tree/) see also https://www.youtube.com/watch?v=j1EXBeBA89w
- "There is no such thing as a fish" (similar to above) (https://www.businessinsider.com/fish-do-not-exist-2016-8)
- Bats are more closely related to cows, whales, and pumas compared to flying squirrels https://www.batcon.org/surprising-bat-relatives/
- Aardvarks are more related to manatees than to armadillos https://www.livescience.com/55241-aardvark-facts.html (bonus: Aardvarks are the only living species of their evolutionary branch)
- New world vultures and old world vultures are not very closely related, it is convergent evolution https://en.wikipedia.org/wiki/New_World_vulture
- Seals are more closely related to dogs than to cats, and even more closely related to bears https://www.youtube.com/watch?v=aAOsf004FqQ
- Shrews are more closely related to cats than to mice (shrews and hedgehogs are in the same order) https://www.youtube.com/shorts/jRPiiXKmZIA
- The malaria parasite shares a surprising common ancestor with kelp and other algae — it even retains a vestigial chloroplast (the apicoplast), inherited from an ancestor that engulfed an alga https://www.youtube.com/watch?v=4ejoVBcLP4U https://en.wikipedia.org/wiki/Apicoplast
- Falcons are more closely related to parrots than to hawks or eagles https://en.wikipedia.org/wiki/Falcon#Systematics_and_evolution
- Crocodiles are more closely related to birds than to lizards (both are archosaurs) https://en.wikipedia.org/wiki/Archosaur
- Termites are actually a family of cockroaches https://en.wikipedia.org/wiki/Termite#Taxonomy
- Red pandas are not closely related to giant pandas — they're in the weasel/raccoon superfamily https://en.wikipedia.org/wiki/Red_panda
- Whales evolved from hoofed land mammals and are closely related to hippos https://en.wikipedia.org/wiki/Evolution_of_cetaceans

### Unusual evolutionary transitions

- Horses used to be smaller and have multiple toes, similar to a tapir, but it was reduced to where they walk on their "middle finger" https://www.sci.news/paleontology/modern-horse-toes-12022.html https://en.wikipedia.org/wiki/Evolution_of_the_horse

### Evolutionary hypotheses

- Eukaryotes evolved from giant viruses? https://en.wikipedia.org/wiki/Viral_eukaryogenesis

### Parent-of-origin effects in citrus

Nearly all commercial citrus are ancient hybrids of just a few progenitor species
(pummelo, citron, mandarin, C. micrantha). These hybrid genomes were "frozen"
because citrus seeds grow clonal embryos from maternal tissue instead of through
normal sexual reproduction. Most seedlings from a citrus seed are clones of the
mother.

Adding confusion: chloroplast DNA is maternally inherited, but citrus unusually
shows paternal inheritance of mitochondrial DNA, so chloroplast, mitochondrial,
and nuclear phylogenies all give different trees.

- https://www.nature.com/articles/nature25447
- https://www.pnas.org/doi/10.1073/pnas.2206076119
- https://academic.oup.com/nsr/article/9/10/nwac114/6608370
- https://www.nature.com/articles/s41467-021-24653-0

## Convergent evolution examples

https://en.wikipedia.org/wiki/List_of_examples_of_convergent_evolution

### Parenting

The concept of 'parental care' evolved independently in many lineages through
convergent evolution

https://en.wikipedia.org/wiki/Parental_care

## Gynandromorphs

Some animals are split male on one side and female on the other — literally half
and half. This happens when sex chromosomes are distributed unevenly during early
cell division, so one half of the body develops as male and the other as female.
It's been documented in birds, butterflies, crustaceans, and insects, and is
sometimes visible as a striking bilateral split in coloring.

https://en.wikipedia.org/wiki/Gynandromorph
https://nautil.us/half-male-half-female-total-animal-234910/

## Dosage compensation and mosaicism

### Calico cats and X inactivation mosaicism

Mammalian females are genetic mosaics: each cell randomly inactivates one X
chromosome early in development, and all descendant cells keep the same X
silenced. In calico cats, X-linked coat color genes on different parental X
chromosomes produce patches of orange and black fur, making the mosaicism
directly visible. This is why calico cats are almost always female — males (XY)
have only one X, so no mosaicism occurs.

https://en.wikipedia.org/wiki/Calico_cat
https://en.wikipedia.org/wiki/X-inactivation

### Dosage compensation solved differently across species

The problem: males and females have different numbers of X chromosomes, so how
do you keep gene output balanced? Each lineage evolved a completely different
solution:

- **Mammals**: silence one female X entirely
- **Drosophila**: double the output of the single male X
- **C. elegans**: halve the output of both hermaphrodite X chromosomes
- **Marsupials**: always silence the paternal X (not random like placental
  mammals)
- **Birds**: no known chromosome-wide compensation — males may just tolerate
  higher expression

https://en.wikipedia.org/wiki/Dosage_compensation

## Genomes

### Large numbers of chromosomes in a butterfly

The Atlas blue butterfly has 448-452 chromosomes — the highest number among
organisms that haven't simply duplicated their whole genome.

https://twitter.com/Jente_O/status/1653469755569782808

See also https://en.wikipedia.org/wiki/List_of_organisms_by_chromosome_count

### Large number of sex chromosomes in platypus

Male platypus has five X and five Y chromosomes. Some of those sex chromosomes
are more similar to bird chromosomes than to other mammal sex chromosomes. The
platypus also lacks the usual mammalian sex-determining gene (SRY), using a
different gene (AMH) instead.

https://en.wikipedia.org/wiki/Platypus#Evolution

https://genomebiology.biomedcentral.com/articles/10.1186/gb-2007-8-11-r243

More complete genome sequencing was done 2021
https://pmc.ncbi.nlm.nih.gov/articles/PMC8081666/

### Organisms without mitochondria

Almost all eukaryotes have mitochondria, so finding one without them was a big
deal. _Monocercomonoides exilis_ is a gut parasite that completely lost its
mitochondria, replacing their essential functions with a system borrowed from
bacteria. Other organisms like _Giardia_ have heavily reduced remnants, but
_Monocercomonoides_ appears to have none at all.

https://en.wikipedia.org/wiki/Monocercomonoides
https://www.cell.com/current-biology/fulltext/S0960-9822(16)30263-9

### Seven different "genomes" in a single celled organism

Like how our cells have a mitochondrial genome alongside the nuclear genome, this
single-celled organism has 7 different genomes in its cell

https://phys.org/news/2023-04-single-celled-alga-harbor-genomes.html

## Horizontal gene transfer

### Bdelloid rotifers — animals full of foreign DNA

Bdelloid rotifers are tiny freshwater animals that haven't had sex in millions of
years. Instead of swapping genes through mating, their genomes are packed with
DNA from bacteria, fungi, and plants — acquired through horizontal gene transfer.
They may pick up foreign genes when they desiccate and rehydrate, temporarily
opening up their DNA to outside fragments. Some of these foreign genes are
functional and help them survive.

https://en.wikipedia.org/wiki/Bdelloid_rotifer
https://www.nature.com/articles/nature07817

## Photosynthetic animals

### Kleptoplasty

Some animals eat algae, digest everything except the chloroplasts, and keep
those chloroplasts functional inside their own cells — literally retaining
another organism's photosynthetic machinery. The sea slug _Elysia chlorotica_
can survive for months on sunlight after a single algal meal this way. Some
acoels (e.g. _Symsagittifera reesei_) similarly retain algal chloroplasts and
can live partly on sunlight. Acoels are themselves phylogenetically odd — long
grouped with flatworms, they're actually among the most basal bilaterian
animals.

https://en.wikipedia.org/wiki/Kleptoplasty
https://en.wikipedia.org/wiki/Elysia_chlorotica
https://en.wikipedia.org/wiki/Acoela

### Photosynthetic salamander

Spotted salamander embryos have algae living _inside_ their cells — the only
known vertebrate with photosynthetic organisms inside its cells. The algae
provide oxygen and the embryo provides CO2 and nutrients.

https://en.wikipedia.org/wiki/Spotted_salamander#Algal_symbiont
https://www.nature.com/articles/news.2010.384

## Myxozoa — animals that became microscopic parasites

Myxozoans are cnidarians (jellyfish relatives) that evolved into tiny parasites,
losing nearly everything that makes an animal recognizable — no gut, no nervous
system, no muscles. Some are just a handful of cells. They were classified as
protists for over a century before molecular evidence revealed they were animals
all along.

https://en.wikipedia.org/wiki/Myxozoa
https://www.smithsonianmag.com/smart-news/parasite-really-micro-jellyfish-180957326/

## Octopus RNA editing

Most animals rely on DNA mutations for genetic variation. Cephalopods (octopuses,
squid, cuttlefish) instead extensively edit their RNA after transcription,
rewriting genetic instructions on the fly. This may help them adapt to
temperature changes rapidly but appears to come at the cost of slower DNA-level
evolution.

https://en.wikipedia.org/wiki/RNA_editing#In_cephalopods
https://www.cell.com/cell/fulltext/S0092-8674(17)30340-6
https://www.nature.com/articles/d41586-017-00612-y

## Wolbachia — the most successful parasite on earth

_Wolbachia_ is a bacterium that infects an estimated 40-60% of all insect
species. It manipulates host reproduction in wild ways: killing males, turning
genetic males into females, or enabling females to reproduce without mating. It
spreads by being passed from mother to offspring and has become so integrated
that some species can no longer survive without it.

https://en.wikipedia.org/wiki/Wolbachia
https://www.nationalgeographic.com/science/article/one-parasite-to-rule-them-all-wolbachia-protects-against-mosquito-borne-diseases

## Immortal jellyfish

_Turritopsis dohrnii_ can revert from its adult medusa form back to its juvenile
polyp stage, essentially restarting its life cycle. It does this by
transdifferentiation — its adult cells transform back into different cell types.

https://en.wikipedia.org/wiki/Turritopsis_dohrnii
https://www.nhm.ac.uk/discover/immortal-jellyfish-secret-to-cheating-death.html

## Cellular

### Multiple-fission cell division

Dental plaque bacteria elongate and then split into 3-14 cells in a single cell
division

https://www.sciencealert.com/bacteria-in-your-mouth-reproduce-in-a-strange-rare-way-scientists-discover

More info https://en.wikipedia.org/wiki/Fission_(biology)#Multiple_fission

## Sex and reproduction

### Parthenogenesis

Parthenogenesis is reproduction where an embryo grows from unfertilized eggs
(https://en.wikipedia.org/wiki/Parthenogenesis)

Some species (e.g. whiptail lizards) are entirely female
(https://www.scienceabc.com/nature/animals/are-there-any-all-female-species-in-the-wild.html)

There are other types of asexual reproduction as well
https://en.wikipedia.org/wiki/Asexual_reproduction

### Species with "more than two sexes"?

https://biology.stackexchange.com/questions/77371/are-there-lifeforms-that-have-more-than-2-sexes

See also https://en.wikipedia.org/wiki/Sexual_system#List_of_sexual_systems

### Male pregnancy

Male seahorses carry and give birth to the young

https://en.wikipedia.org/wiki/Male_pregnancy

### Sexual cannibalism

Sexual cannibalism is common across the tree of life
https://en.wikipedia.org/wiki/Sexual_cannibalism

There are other types of cannibalism also
https://en.wikipedia.org/wiki/Cannibalism

See also: trophic eggs (eggs as food) https://en.wikipedia.org/wiki/Trophic_egg

### Traumatic insemination

A number of examples listed here https://en.wikipedia.org/wiki/Sexual_conflict

### Odd genitalia

- Kangaroos have "three vaginas" https://grist.org/animals/kangaroo-genitals-are-weirder-than-you-ever-thought-possible-2/

## Send PRs for more things!
