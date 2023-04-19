# Gene Variant Transcriptions

In this analisis I am interested into observing whether there is a difference into variant transcriptions over the replications as well as the gene class.

## The Data

The data that is going to be used in this analysis has the following variables

|Variable    | Description                                      |
|------------|--------------------------------------------------|
|`SUMOvar`   | Class of SUMO gene in format `SxVx`              |
|`XCopies`   | $10^x$ number of copies                          |
|`Replicate1`| Variant transcription in first replicate         |
|`Replicate2`| Variant transcription in second replicate        |
|`Replicate3`| Variant transcription in third replicate         |
|`AverageCQ` | Average variant transcription over the replicates|

## Average CQ over $10^x$ Copies

The following plot shows the average CQ for the three replications of each group. Note the increasing tendency as the number of copies decrease.

![Averag Cq over number of copies by gene](/Image/averageCq.png)

## Gene Variant Transcription over replicates

In the following slope charts we visualize the variant transcriptions for each group on each of the replications.

Note that in the S1V1, S1V2 and S1V3 there is no variation in the replications. In the S2V1 class, copy 4, we can see some unusual observation. Also, there is some variation between replication 1 and 2 in the other classes, but not substantial difference between replication 2 and 3.


![Gene variant transcription over replicates by group](/Image/geneVT.png)
