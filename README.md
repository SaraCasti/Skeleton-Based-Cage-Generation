# Skeleton-Based-Cage-Generation
Source code of the paper "Skeleton Based Cage Generation Guided by Harmonic Fields"
S. Casti, M. Livesu, N. Mellado, N. Abu Rumman, R. Scateni, L. Barthe, E. Puppo

We propose a novel user-assisted cage generation tool. We start from a digital character and its skeleton, and create a coarse control cage for its animation. Our method requires minimal interaction to select bending points on the skeleton, and computes the corresponding cage automatically. The key contribution is a volumetric field defined in the interior of the character and embedding the skeleton. The integral lines of such field are used to propagate cutting surfaces from the interior of the character to its skin, and allow us to robustly trace non-planar cross sections that adapt to the local shape of the character.
Our method overcomes previous approaches that rely on the popular (but tedious and limiting) cutting planes. 
We validated our software on a variety of digital characters. Our final cages are coarse yet entirely compliant with the structure induced by the underlying skeleton, enriched with the semantics provided by the bending points selected by the user. Automatic placement of bending nodes for a fully automatic caging pipeline is also supported.
