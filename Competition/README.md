## Competition rules
### Teams
Teams should consist of 1-3 members. Please name the team - name will appear in the results table (can be anything you come up with but please avoid PII data in the group name e.g. surnames).

### Dataset and competition's goal
Goal of the competition is to achieve highest:
* Groups 11 and 13 - **[accuracy](https://en.wikipedia.org/wiki/Accuracy_and_precision)**
* Group 12 - **[F1-score](https://en.wikipedia.org/wiki/F-score)**

in classification of target variable **IsIPA**. To create a model please use **IPA.csv** dataset (used it for both train and validation dataset) and predict labels on **IPA_test.csv** data. Description of dataset features can be found in **IPA_description.txt**.

### Results delivery
Please send the results to _lkrain@sgh.waw.pl_ by the end of the class.

In the e-mail please specify name of the group and members. Required attachments are:
1. R/Python/Julia script or notebook with used code
2. CSV file named **[group_name]_IPA_prediction.csv** with one column named **Prediction** containing 5000 predictions with values 1/0 or TRUE/FALSE for dataset **IPA_test.csv**. Please make sure predictions order is the same as rows in test data.  

Table with ranking will appear in this README file. Best team in each course group will receive 5 points, next 4 points, etc.

Good luck!

### Competition results

Group 11
| **Team**     | **Accuracy** | **Points** | **Language** | **Model**                  |
|----------------|--------------|------------|-----------|----------------------------|
| Omega        | 86,76        | 5          | Python    | Random Forest                    |
| Booster Team            | 86,62         | 4          | R    | XGBoost                    |
| Lion           | 59,94       | 3          | R    | Random Forest |

Group 12
| **Team**     | **F1-Score** | **Points** | **Language** | **Model**                  |
|----------------|--------------|------------|-----------|----------------------------|
| Komes Enjoyer        | 78,43        | 5          | Python    | Random Forest                    |
| xyz           | 78,08         | 4          | Julia    | Random Forest                   |
| The Crusaders           | 78,03      | 3          | Python    | Random Forest |
| SLM Experts        | 76,77      | 2          | Python    | Random Forest |
| KT          | 72,15       | 1         | Python    | Random Forest |
| Malatya          | 31,27       | 0          | Python    | Random Forest |

Group 13
| **Team**     | **Accuracy** | **Points** | **Language** | **Model**                  |
|----------------|--------------|------------|-----------|----------------------------|
| Pikachu        | 87,00        | 5          | Python    | LightGBM                   |
| KMK            | 86,80         | 4          | Python    | Random Forest                   |
| Turko           | 84,10      | 3          | Python    | Logistic Regression |
| Drunk Peekachu           | 83,86       | 2          | Python    | Logistic Regression |
| SP           | 71,68      | 1          | R    | Logistic Regression |
