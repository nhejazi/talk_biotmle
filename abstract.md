The widespread availability of high-dimensional data has catalyzed the process
of biological pattern discovery. Today, the simultaneous screening of anywhere
from thousands to millions of biological characteristics (in, e.g., genomics,
metabolomics, proteomics, etc.) is commonplace in many experimental settings,
making the simultaneous screening of such a large number of characteristics
a central problem in computational biology and allied sciences. The information
gleaned from such studies promises substantial progress, not only for the basic
sciences but also for medicine and public health. While the tools of modern
chemical biology and biophysics allow for great precision in probing biological
systems at the molecular-cellular level, population biomedical and public health
sciences must operate without access to such a fine level of control. Instead,
statistical innovations bridge the gap -- being used to dissect mechanistic
processes and to mitigate the inferential obstacles imposed by the confounding
of key relationships in observational (non-randomized) studies. Unfortunately,
most off-the-shelf statistical techniques rely on restrictive assumptions --
born of mathematical convenience -- that invite opportunities for bias due to
model misspecification (when the biological process under study fails to obey
the assumed mathematical conveniences). Fortunately, model-agnostic inference,
which draws on causal inference and semiparametric efficiency theory, provides
an avenue for avoiding restrictive modeling assumptions while obtaining robust
statistical inference about scientifically relevant parameters. We outline this
framework briefly and introduce a model-agnostic approach to biomarker discovery
incorporating causal inference-based parameters, leveraging state-of-the-art
machine learning for flexible estimation (to mitigate potential for model
misspecification), and utilizing variance moderation (to curb Type-I error) to
deliver stable inference in high-dimensional settings, even when sample sizes
are limited. When paired with domain expertise, this approach reliably
identifies biomarkers linked to disease or exposure patterns, yielding insights
for future investigations into therapeutics and policy interventions. The
approach is implemented in the open-source biotmle R/Bioconductor package
(https://bioconductor.org/biotmle). This talk is based on joint work with Alan
Hubbard, Mark van der Laan, and Philippe Boileau, described in the pre-print:
https://arxiv.org/abs/1710.05451.
