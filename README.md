# BBQCG-PT
This is a repository with data related to the dataset for bitstream-based video auality assessment of Cloud Gaming Services submitted to QoMEX 2024.
This work is conducted within ITU-T SG12/Q14 under the work item [P.BBQCG - Parametric bitstream-based Quality Assessment of Cloud Gaming Services](https://www.itu.int/ITU-T/workprog/wp_item.aspx?isn=17809).

If you use any of the data please cite the following paper

```bibtex
@inproceedings{lindero2024bbqcg,
    author = {David Lindero and Steven Schmidt and Rakesh Rao Ramachandra Rao and Saman Zadtootaghaj and Anthony Adeyemi-Ejeye and Maria Laura Mele and Damon Millar and Cise Midoglu and Saeed Shafiee Sabet and Mathias Wien},
    booktitle={2024 IEEE 16th International Conference on Quality of Multimedia Experience (QoMEX)}, 
    title={BBQCG-PT: A Subjective Dataset for Bitstream-based Video Quality Assessment of Cloud Gaming Services}, 
    year={2024},
    note = {submitted}
}
```

## Structure

* `objective_scores` : a folder consisting of 2 csv files: `p1204_3_h264_h265.csv` and `p1204_3_av1.csv`. The csv files contain P.1204.3 model prediction scores, see [P.1204.3](https://github.com/Telecommunication-Telemedia-Assessment/bitstream_mode3_p1204_3). The csv files also contain all the bitstream features used for P.1204.3 score prediction.
* `subjective_scored` : scores from the subjective test for 2 source videos (`sports_01` and `racing_01`), exported from [AVRateNG](https://github.com/Telecommunication-Telemedia-Assessment/avrateNG)