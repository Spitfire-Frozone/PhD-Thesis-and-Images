## Images
The images in this folder in this repository are ones that I have created myself. These are free for you to use but please use the following reference. 
~~~
@book{SpiteriVHbbPhDThesis,
      author        = "Spiteri, D",
      title         = "Higgs boson studies: associated production with a vector boson and decay into b-quarks using the ATLAS Run-2 dataset",
      collaboration = "ATLAS",
      year          = "2021",
      note          = "Doctoral Thesis",
      url           = "http://theses.gla.ac.uk/id/eprint/81897",
}
~~~

## Tex-Templates
For the images that were completed using tex, you might find counterpart files in my [Tex Templates Directory](https://github.com/Spitfire-Frozone/Tex-Templates) such that you can replicate similar images for yourself. I'm no expert, but you can use these as a starting point.

## Captions
The following captions are slightly edited versions of the original captions accompanying these images from my thesis. This is to add some context and explain the images where necessary. Otherwise, they are .tex compatible.

### ATLASTrackParams.pdf
> Pictorial definition of the parameters that make up a track at the ATLAS detector. All of the parameters are defined with respect to a perigee surface, shown here in blue. The transverse momentum ($\vec{\pt}$) is the 2-D projection of the total momentum of the track ($\vec{p}$) at the distance of closest approach onto the perigee surface. The $B$ subscript on the axis directions refers to the beam, which travels in the z-direction.

### AnalysisWorkflowEdit.pdf
> Picture showing the rough workflow of the analysis. Black lines represent data, blue lines represent Monte Carlo Simulations, red lines represent systematics. Green curved lines are packages in the analysis. Detector-based systematics are propagated to Monte Carlo Simulations into the xAOD format and end up being stored in CxAOD's as 'shallow copies'.

### HiggsBranchingFracs.png
> Pie chart showing the decay ratios of the Higgs boson to other particles. Even though pairs of W- and Z-bosons are heavier than the Higgs rest mass, the masses of the virtual particles can differ from the nominal masses such that the decay is still kinematically possible. This is known as being produced 'off-shell' and the asterisk shows that at least one of the particles is produced in this manner. The Higgs boson also can decay into gluons via an intermediate (top) quark loop. These branching fractions are dependent on the energy of the Higgs particles. These ratios are taken from a Higgs with its nominal mass.

### JetAlgorithms.pdf
> A graphic giving a brief overview of the types of jet algorithm that exist. $y_i$, $\phi_i$ and $p_{T,i}$, are the rapidity, azimuthal angle, and the transverse momentum of the candidate object to be added to the jet; $B$ is the beampipe; $R$ is the radius of the jet cone, and $\Delta R_{ij}$ is the radial distance between the candidate and 'seed' jet object.

### MC.pdf
> Diagram showing how the Monte Carlo Integration method is used to evaluate the integral of p(x) between the points 'a' and 'b'. The integrating volume is given by the area between the points a and b on the $x$-axis extended up to the line $y$ = c. Points are randomly sampled in [$x,y$] and those that are less than p(x) are called 'hits' while those that are larger than p(x) are called 'misses'.

### MCTracks.pdf
> Graphic showing how Monte Carlo simulated truth tracks and reconstructed track objects are made.

### SM.pdf
> Depiction of the Standard Model. There are seventeen particles, antiparticles notwithstanding, shown as spheres consisting of five bosons and twelve fermions. The particles known as fermions are all on the central plinth. Quarks are depicted in blue, charged leptons in yellow/gold and the neutrinos in red. The quarks are separated into two rows; the top row has a fundamental electric charge of $\frac{2}{3}$ while the bottom has a fundamental electric charge of $-\frac{1}{3}$. The force-carrying bosons have interactions with all particles of the colour of the bars that come off the central plinth. All particles on plinths have interactions with all other particles on all levels higher than it, i.e. the gluon will interact only with the quarks but the photon will interact with both the quarks and the charged leptons but not the gluon. The exception to this is the W-boson as it has electromagnetic charge, so can interact with a photon. The fermion plinth is divided into three groups of particles called generations. Between each generation all the quantum numbers barring flavour are the same but the higher the generation number the more massive the rest mass of the particles. All particles in white text are massive, and the sizes of the spheres are indicators of the relative masses of the particles with the exception of the electron and neutrinos which would be too small so have been scaled up. All particles in black text are massless. The Higgs particle interacts with all massive particles. If the white-gradient shading on the ball is to the bottom right then these particles interact with the Higgs via the Higgs Mechanism, and if the black-gradient shading on the particle ball is to the bottom left then the interactions with the Higgs are via the Yukawa interaction.

### TrackSeeds.pdf
> Image showing the different objects that are formed while creating tracks at the ATLAS experiment. Charged particle interactions with detector components induce electrical signals which in turn inform the position of this interaction. This information is contained within space points, shown as yellow points. These points are combined to form track 'seeds' which are cyan if they are formed in the Semiconductor Tracker (SSS seeds); and navy blue if they are formed in the Pixel system (PPP seeds). The momentum information from the seeds is then extended to find other points that lie on this to form silicon track candidates (shown in dashed green). The third track going clockwise shows the tracks are then extended into the Transition Radiation Tracker (TRT) to see if they align with TRT deposits. Track candidates that fulfil further quality requirements become tracks, shown in red. The lighter red track has one pixel 'hole' and one Semiconductor Tracker 'hole' so passes loose track requirements, and the darker red track has hits in every layer, so passes the tight track requirement. The two track candidates left in the diagram do not become actual tracks because they either miss the nominal interaction point when extended, or do not have any unique space points attributed to the track in the pixel system.

### VHbb.pdf
> Feynman diagram showing the full Higgsstrahlung process of Higgs production at the LHC, and its decay into the final states of interest to the analysis. Gluon initiated (rather than quark) diagrams do exist but they require two additional vertices (points where three or more particles meet) and are thus rarer.

### qobsPDF2.pdf
> Upon measurement of $q_{obs}$, the alternative hypothesis is rejected as the $q_{obs}$ is smaller than the p-value set. The significance of the result is given by $Z$, the number of standard deviations by which the central values of $q_{H_0}$ and $q_{obs}$ are separated. Image generated using [this website](https://www.transum.org/Maths/Activity/Graph/Desmos.asp).
