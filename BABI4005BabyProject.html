{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "420e37a7-0241-4624-b274-1d82ec7b3a88",
   "metadata": {},
   "source": [
    "# Sleep Study Dataset Analysis"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "ef34fe8b-2eae-4c3a-bde3-645f6f10f48d",
   "metadata": {},
   "source": [
    "My goal for this analysis was to understand human sleep behaviour using the \"sleepstudy.csv\" dataset. The dataset has information about the sleep duration, efficieny, REM, deep, and light sleep percentages of the participants. As well as some lifestyle factors like caffeine and alcohol consumption, exercise frequency, and smoking status. Using this data I had the goal to understand how demographic facotrs and habits in the daily life influence sleep quality and duration. \n",
    "\n",
    "This analysis will include statistics, visualizations, and correlations to provide insights into which factors are most strongly associated with better or worse sleep. Understanding the patterns in the dataset can help with knowing healthier habits for sleep and overall lifestyle."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "72cca437-977f-4301-8fd1-4593978dbe64",
   "metadata": {},
   "outputs": [],
   "source": [
    "#Import Libraries\n",
    "import pandas as pd\n",
    "import matplotlib.pyplot as plt\n",
    "import seaborn as sns"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "fef6818f-1eb6-4294-b0fc-a6dceb266b77",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>Age</th>\n",
       "      <th>Gender</th>\n",
       "      <th>Bedtime</th>\n",
       "      <th>WakeupTime</th>\n",
       "      <th>SleepDuration</th>\n",
       "      <th>SleepEfficiency</th>\n",
       "      <th>REMSleepPercentage</th>\n",
       "      <th>DeepSleepPercentage</th>\n",
       "      <th>LightSleepPercentage</th>\n",
       "      <th>Awakenings</th>\n",
       "      <th>CaffeineConsumption</th>\n",
       "      <th>AlcoholConsumption</th>\n",
       "      <th>SmokingStatus</th>\n",
       "      <th>ExerciseFrequency</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>0</th>\n",
       "      <td>1</td>\n",
       "      <td>80</td>\n",
       "      <td>Female</td>\n",
       "      <td>2025-09-30 7:32</td>\n",
       "      <td>49:16.7</td>\n",
       "      <td>6.283241</td>\n",
       "      <td>0.57</td>\n",
       "      <td>15</td>\n",
       "      <td>35</td>\n",
       "      <td>50</td>\n",
       "      <td>0</td>\n",
       "      <td>25.0</td>\n",
       "      <td>1</td>\n",
       "      <td>Yes</td>\n",
       "      <td>1</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>1</th>\n",
       "      <td>2</td>\n",
       "      <td>24</td>\n",
       "      <td>Male</td>\n",
       "      <td>2025-06-29 20:59</td>\n",
       "      <td>09:10.2</td>\n",
       "      <td>7.155613</td>\n",
       "      <td>0.91</td>\n",
       "      <td>29</td>\n",
       "      <td>68</td>\n",
       "      <td>3</td>\n",
       "      <td>4</td>\n",
       "      <td>50.0</td>\n",
       "      <td>0</td>\n",
       "      <td>No</td>\n",
       "      <td>2</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>2</th>\n",
       "      <td>3</td>\n",
       "      <td>37</td>\n",
       "      <td>Male</td>\n",
       "      <td>2025-12-24 21:28</td>\n",
       "      <td>31:34.3</td>\n",
       "      <td>6.050627</td>\n",
       "      <td>0.58</td>\n",
       "      <td>15</td>\n",
       "      <td>35</td>\n",
       "      <td>50</td>\n",
       "      <td>3</td>\n",
       "      <td>50.0</td>\n",
       "      <td>0</td>\n",
       "      <td>No</td>\n",
       "      <td>5</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>3</th>\n",
       "      <td>4</td>\n",
       "      <td>68</td>\n",
       "      <td>Female</td>\n",
       "      <td>2025-02-22 0:25</td>\n",
       "      <td>26:37.0</td>\n",
       "      <td>7.017791</td>\n",
       "      <td>0.88</td>\n",
       "      <td>28</td>\n",
       "      <td>44</td>\n",
       "      <td>28</td>\n",
       "      <td>1</td>\n",
       "      <td>50.0</td>\n",
       "      <td>0</td>\n",
       "      <td>Yes</td>\n",
       "      <td>4</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>4</th>\n",
       "      <td>5</td>\n",
       "      <td>58</td>\n",
       "      <td>Male</td>\n",
       "      <td>2025-09-02 12:31</td>\n",
       "      <td>17:46.3</td>\n",
       "      <td>8.764793</td>\n",
       "      <td>0.95</td>\n",
       "      <td>28</td>\n",
       "      <td>40</td>\n",
       "      <td>32</td>\n",
       "      <td>4</td>\n",
       "      <td>25.0</td>\n",
       "      <td>4</td>\n",
       "      <td>No</td>\n",
       "      <td>4</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "   ID  Age  Gender           Bedtime WakeupTime  SleepDuration  \\\n",
       "0   1   80  Female   2025-09-30 7:32    49:16.7       6.283241   \n",
       "1   2   24    Male  2025-06-29 20:59    09:10.2       7.155613   \n",
       "2   3   37    Male  2025-12-24 21:28    31:34.3       6.050627   \n",
       "3   4   68  Female   2025-02-22 0:25    26:37.0       7.017791   \n",
       "4   5   58    Male  2025-09-02 12:31    17:46.3       8.764793   \n",
       "\n",
       "   SleepEfficiency  REMSleepPercentage  DeepSleepPercentage  \\\n",
       "0             0.57                  15                   35   \n",
       "1             0.91                  29                   68   \n",
       "2             0.58                  15                   35   \n",
       "3             0.88                  28                   44   \n",
       "4             0.95                  28                   40   \n",
       "\n",
       "   LightSleepPercentage  Awakenings  CaffeineConsumption  AlcoholConsumption  \\\n",
       "0                    50           0                 25.0                   1   \n",
       "1                     3           4                 50.0                   0   \n",
       "2                    50           3                 50.0                   0   \n",
       "3                    28           1                 50.0                   0   \n",
       "4                    32           4                 25.0                   4   \n",
       "\n",
       "  SmokingStatus  ExerciseFrequency  \n",
       "0           Yes                  1  \n",
       "1            No                  2  \n",
       "2            No                  5  \n",
       "3           Yes                  4  \n",
       "4            No                  4  "
      ]
     },
     "execution_count": 2,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Load csv file and check if it loaded correctly\n",
    "df = pd.read_csv(\"sleepstudy.csv\")\n",
    "df.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "e56dfacf-f842-4078-b44e-4e6280bbac70",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/html": [
       "<div>\n",
       "<style scoped>\n",
       "    .dataframe tbody tr th:only-of-type {\n",
       "        vertical-align: middle;\n",
       "    }\n",
       "\n",
       "    .dataframe tbody tr th {\n",
       "        vertical-align: top;\n",
       "    }\n",
       "\n",
       "    .dataframe thead th {\n",
       "        text-align: right;\n",
       "    }\n",
       "</style>\n",
       "<table border=\"1\" class=\"dataframe\">\n",
       "  <thead>\n",
       "    <tr style=\"text-align: right;\">\n",
       "      <th></th>\n",
       "      <th>ID</th>\n",
       "      <th>Age</th>\n",
       "      <th>Gender</th>\n",
       "      <th>Bedtime</th>\n",
       "      <th>WakeupTime</th>\n",
       "      <th>SleepDuration</th>\n",
       "      <th>SleepEfficiency</th>\n",
       "      <th>REMSleepPercentage</th>\n",
       "      <th>DeepSleepPercentage</th>\n",
       "      <th>LightSleepPercentage</th>\n",
       "      <th>Awakenings</th>\n",
       "      <th>CaffeineConsumption</th>\n",
       "      <th>AlcoholConsumption</th>\n",
       "      <th>SmokingStatus</th>\n",
       "      <th>ExerciseFrequency</th>\n",
       "    </tr>\n",
       "  </thead>\n",
       "  <tbody>\n",
       "    <tr>\n",
       "      <th>count</th>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000</td>\n",
       "      <td>1000</td>\n",
       "      <td>1000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>744.000000</td>\n",
       "      <td>1000.000000</td>\n",
       "      <td>1000</td>\n",
       "      <td>1000.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>unique</th>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>2</td>\n",
       "      <td>1000</td>\n",
       "      <td>990</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>2</td>\n",
       "      <td>NaN</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>top</th>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>Male</td>\n",
       "      <td>2025-09-30 7:32</td>\n",
       "      <td>42:25.2</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>Yes</td>\n",
       "      <td>NaN</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>freq</th>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>513</td>\n",
       "      <td>1</td>\n",
       "      <td>2</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>513</td>\n",
       "      <td>NaN</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>mean</th>\n",
       "      <td>500.500000</td>\n",
       "      <td>50.125000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>7.027443</td>\n",
       "      <td>0.720150</td>\n",
       "      <td>22.460000</td>\n",
       "      <td>47.357000</td>\n",
       "      <td>30.183000</td>\n",
       "      <td>2.539000</td>\n",
       "      <td>25.168011</td>\n",
       "      <td>2.560000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>2.565000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>std</th>\n",
       "      <td>288.819436</td>\n",
       "      <td>18.076397</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>1.135365</td>\n",
       "      <td>0.128139</td>\n",
       "      <td>4.589059</td>\n",
       "      <td>13.097293</td>\n",
       "      <td>13.788968</td>\n",
       "      <td>1.726691</td>\n",
       "      <td>20.446036</td>\n",
       "      <td>1.746267</td>\n",
       "      <td>NaN</td>\n",
       "      <td>1.712515</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>min</th>\n",
       "      <td>1.000000</td>\n",
       "      <td>18.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>5.002335</td>\n",
       "      <td>0.500000</td>\n",
       "      <td>15.000000</td>\n",
       "      <td>25.000000</td>\n",
       "      <td>1.000000</td>\n",
       "      <td>0.000000</td>\n",
       "      <td>0.000000</td>\n",
       "      <td>0.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>0.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>25%</th>\n",
       "      <td>250.750000</td>\n",
       "      <td>34.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>6.076980</td>\n",
       "      <td>0.610000</td>\n",
       "      <td>18.000000</td>\n",
       "      <td>36.000000</td>\n",
       "      <td>18.000000</td>\n",
       "      <td>1.000000</td>\n",
       "      <td>0.000000</td>\n",
       "      <td>1.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>1.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>50%</th>\n",
       "      <td>500.500000</td>\n",
       "      <td>51.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>6.981505</td>\n",
       "      <td>0.720000</td>\n",
       "      <td>22.000000</td>\n",
       "      <td>47.000000</td>\n",
       "      <td>30.000000</td>\n",
       "      <td>3.000000</td>\n",
       "      <td>25.000000</td>\n",
       "      <td>3.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>3.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>75%</th>\n",
       "      <td>750.250000</td>\n",
       "      <td>65.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>8.039587</td>\n",
       "      <td>0.830000</td>\n",
       "      <td>27.000000</td>\n",
       "      <td>59.000000</td>\n",
       "      <td>42.000000</td>\n",
       "      <td>4.000000</td>\n",
       "      <td>50.000000</td>\n",
       "      <td>4.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>4.000000</td>\n",
       "    </tr>\n",
       "    <tr>\n",
       "      <th>max</th>\n",
       "      <td>1000.000000</td>\n",
       "      <td>80.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>NaN</td>\n",
       "      <td>8.998650</td>\n",
       "      <td>0.950000</td>\n",
       "      <td>30.000000</td>\n",
       "      <td>70.000000</td>\n",
       "      <td>59.000000</td>\n",
       "      <td>5.000000</td>\n",
       "      <td>50.000000</td>\n",
       "      <td>5.000000</td>\n",
       "      <td>NaN</td>\n",
       "      <td>5.000000</td>\n",
       "    </tr>\n",
       "  </tbody>\n",
       "</table>\n",
       "</div>"
      ],
      "text/plain": [
       "                 ID          Age Gender          Bedtime WakeupTime  \\\n",
       "count   1000.000000  1000.000000   1000             1000       1000   \n",
       "unique          NaN          NaN      2             1000        990   \n",
       "top             NaN          NaN   Male  2025-09-30 7:32    42:25.2   \n",
       "freq            NaN          NaN    513                1          2   \n",
       "mean     500.500000    50.125000    NaN              NaN        NaN   \n",
       "std      288.819436    18.076397    NaN              NaN        NaN   \n",
       "min        1.000000    18.000000    NaN              NaN        NaN   \n",
       "25%      250.750000    34.000000    NaN              NaN        NaN   \n",
       "50%      500.500000    51.000000    NaN              NaN        NaN   \n",
       "75%      750.250000    65.000000    NaN              NaN        NaN   \n",
       "max     1000.000000    80.000000    NaN              NaN        NaN   \n",
       "\n",
       "        SleepDuration  SleepEfficiency  REMSleepPercentage  \\\n",
       "count     1000.000000      1000.000000         1000.000000   \n",
       "unique            NaN              NaN                 NaN   \n",
       "top               NaN              NaN                 NaN   \n",
       "freq              NaN              NaN                 NaN   \n",
       "mean         7.027443         0.720150           22.460000   \n",
       "std          1.135365         0.128139            4.589059   \n",
       "min          5.002335         0.500000           15.000000   \n",
       "25%          6.076980         0.610000           18.000000   \n",
       "50%          6.981505         0.720000           22.000000   \n",
       "75%          8.039587         0.830000           27.000000   \n",
       "max          8.998650         0.950000           30.000000   \n",
       "\n",
       "        DeepSleepPercentage  LightSleepPercentage   Awakenings  \\\n",
       "count           1000.000000           1000.000000  1000.000000   \n",
       "unique                  NaN                   NaN          NaN   \n",
       "top                     NaN                   NaN          NaN   \n",
       "freq                    NaN                   NaN          NaN   \n",
       "mean              47.357000             30.183000     2.539000   \n",
       "std               13.097293             13.788968     1.726691   \n",
       "min               25.000000              1.000000     0.000000   \n",
       "25%               36.000000             18.000000     1.000000   \n",
       "50%               47.000000             30.000000     3.000000   \n",
       "75%               59.000000             42.000000     4.000000   \n",
       "max               70.000000             59.000000     5.000000   \n",
       "\n",
       "        CaffeineConsumption  AlcoholConsumption SmokingStatus  \\\n",
       "count            744.000000         1000.000000          1000   \n",
       "unique                  NaN                 NaN             2   \n",
       "top                     NaN                 NaN           Yes   \n",
       "freq                    NaN                 NaN           513   \n",
       "mean              25.168011            2.560000           NaN   \n",
       "std               20.446036            1.746267           NaN   \n",
       "min                0.000000            0.000000           NaN   \n",
       "25%                0.000000            1.000000           NaN   \n",
       "50%               25.000000            3.000000           NaN   \n",
       "75%               50.000000            4.000000           NaN   \n",
       "max               50.000000            5.000000           NaN   \n",
       "\n",
       "        ExerciseFrequency  \n",
       "count         1000.000000  \n",
       "unique                NaN  \n",
       "top                   NaN  \n",
       "freq                  NaN  \n",
       "mean             2.565000  \n",
       "std              1.712515  \n",
       "min              0.000000  \n",
       "25%              1.000000  \n",
       "50%              3.000000  \n",
       "75%              4.000000  \n",
       "max              5.000000  "
      ]
     },
     "execution_count": 3,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Summary Statistics\n",
    "df.describe(include = \"all\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "c481926d-38e1-4d67-8487-c363de8fcad1",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "ID                        0\n",
       "Age                       0\n",
       "Gender                    0\n",
       "Bedtime                   0\n",
       "WakeupTime                0\n",
       "SleepDuration             0\n",
       "SleepEfficiency           0\n",
       "REMSleepPercentage        0\n",
       "DeepSleepPercentage       0\n",
       "LightSleepPercentage      0\n",
       "Awakenings                0\n",
       "CaffeineConsumption     256\n",
       "AlcoholConsumption        0\n",
       "SmokingStatus             0\n",
       "ExerciseFrequency         0\n",
       "dtype: int64"
      ]
     },
     "execution_count": 4,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Count missing values in each column\n",
    "df.isnull().sum()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "60efd2d1-856e-4f86-9049-e1c51af2092d",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(1000, 15)"
      ]
     },
     "execution_count": 5,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Shape of dataset to help with Basic Summary section\n",
    "df.shape"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "99884b9f-9a90-4c98-be2c-d093235363c6",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "51.3\n"
     ]
    }
   ],
   "source": [
    "#Figuring out the percentage of smokers for descriptive insights\n",
    "\n",
    "smoker_percentage = (df['SmokingStatus'] == 'Yes').mean() * 100\n",
    "print(round(smoker_percentage, 2))\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "521da03d-9536-48be-bd20-5fb2a1e9974a",
   "metadata": {},
   "source": [
    "## Basic Summary"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "55cfeccf-7ffe-4288-8f32-73636cdd0477",
   "metadata": {},
   "source": [
    "This dataset has info on participants sleep paterns and lifestyle habits. Columns include SleepDuration, SleepEfficiency, REMSleepPercentage, DeepSleepPercentage, LightSleepPercentage, lifestyle habits like CaffeineConsumption, AlcoholConsumption, SmokingStatus, and ExerciseFrequency, along with Age and Gender. There are 1000 columns and 15 rows with 256 entries in \"CaffeineConsumption\" being blank."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "aec79ef3-d403-47e3-9a63-141a29530826",
   "metadata": {},
   "source": [
    "## Descriptive Statistics"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3e5ab7e9-a77f-48f4-b227-fcda71d70826",
   "metadata": {},
   "source": [
    "### Age"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1060e821-220d-4862-9562-66f7a9de5180",
   "metadata": {},
   "source": [
    "Participants range from 18-80 years old, wiht a median age of 51. The IQR shows that most participants are on the older side (34-65)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f10ff787-bc1c-40dd-99e9-9159820b49bb",
   "metadata": {},
   "source": [
    "### Sleep Duration"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "4c20edb2-b225-419f-aae0-2b6771dfa953",
   "metadata": {},
   "source": [
    "On average participants sleep about 7 hours per night (mean = 7.027 hours), with a range of 5 to 9 hours across the whole dataset. Most of the dataset falls between the 6-8 hour range (the IQR)."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6a2fca92-bc1d-4554-98d0-1231d0d84d56",
   "metadata": {},
   "source": [
    "### Sleep Efficiency"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7b8a4b5d-be42-453c-b878-b6c9bdd23ff1",
   "metadata": {},
   "source": [
    "Average sleep efficency is around 72% with most participants between 61% and 83% (the 25th and 75th percentile respect). Some participants however, have very low sleep efficency (50%), while some reach a very high efficiency (95%)."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "68987914-8172-4124-ba57-bea71a63e830",
   "metadata": {},
   "source": [
    "### Sleep Stages"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7cc9c971-4744-4d93-83a2-b7e100453730",
   "metadata": {},
   "source": [
    "REM Sleep (~22% of total sleep):\n",
    "\n",
    "REM (Rapid Eye Movement) sleep is the stage of sleep where dreaming occurs, characterized by high brain activity, increased heart rate, and temporary paralysis of major muscles. REM sleep is CRUCIAL for high quality sleep with the optimal amount comprising of 20-25% of your total sleep duration (essentially too much is bad). Participants spend roughs a fifth of their sleep in REM, which is normal.\n",
    "\n",
    "Source: National Institutes of Health (https://www.nhlbi.nih.gov/health/sleep/stages-of-sleep and https://pmc.ncbi.nlm.nih.gov/articles/PMC2847051/)\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "9f1d1219-493b-44d9-8e39-38185118716b",
   "metadata": {},
   "source": [
    "Deep Sleep (~47% of total sleep):\n",
    "\n",
    "Deep sleep is the most restorative stage of sleep. It helps the body recover, strengthens the immunge system, and supports muscle and tissue repair. Deep sleep is the largest portion of sleep. This number indicates participants are getting enough restorative sleep even when the total sleep duration varies.\n",
    "\n",
    "Source: Sleep Foundation (https://www.sleepfoundation.org/stages-of-sleep/deep-sleep)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5d28cba0-ce9a-4f74-88ed-05a2e34fc822",
   "metadata": {},
   "source": [
    "Light Sleep (~30% of total sleep):\n",
    "\n",
    "Light sleep is the stage between waking up and deep sleep. Easier to wake up from and plays a role in physical recover and memory consolidation but is lest restorative than deep sleep. Participants spend about 30% which is normal.\n",
    "\n",
    "Source: CLMSleep (https://www.clmsleep.com/light-sleep/)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7b5c5ad8-9832-481a-bb5b-7e7953424bf3",
   "metadata": {},
   "source": [
    "### Awakenings"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e1fd7332-8f28-4449-b1c0-6e490e495f51",
   "metadata": {},
   "source": [
    "Participants experience 0-5 awakenings per night, with a median of 3, suggesting sleep interruptions are common. Upon research, sleepless nights are  common with approximately 2 in 5 Canadians experiencing sleepless nights according to Stats Canada.\n",
    "\n",
    "Source: Statistics Canada (https://www.statcan.gc.ca/o1/en/plus/1653-cant-sleep-count-sheep)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3b6369dc-2626-43a0-baf9-8a04b15c40ad",
   "metadata": {},
   "source": [
    "### Lifestyle Factors"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "ed133365-2b97-49bd-972f-d6f96c9fe1da",
   "metadata": {},
   "source": [
    "Exercise Frequency: Most participants exercise 0-5 days per week (median 3). More frequent exercise is generally linked to better sleep quality\n",
    "\n",
    "Caffeine Consumption: Caffeine intake varies widely (0-50 mg/day). Higher caffeince use may reduce sleep duration or efficiency\n",
    "\n",
    "Alcohol Consumption: Alcohol consumption ranges 0-5 ounces per day. Higher alcohol can interrupt sleep cycles and ruin sleep quality\n",
    "\n",
    "Smoking Status: About half of the participants being smokers. Nicotine can negatively effect sleep duration and efficiency"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5e539536-6192-49a6-8092-a28888dfab4f",
   "metadata": {},
   "source": [
    "## Visual Analysis"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c11a32b3-ced7-4ab0-baf9-b5577fb8b532",
   "metadata": {},
   "source": [
    "### Distribution of Sleep Duration"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "3b406510-bd0d-4502-8512-7b8e7e534e7e",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/png": "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Pn/+fO/vBw4ccO677z4nJibGKVy4sHP33XebC+b5euedd8z1n/Q6UNWrVzcXjvPQZXWdH374odOkSROzjF4XybcMnmV+/vnnqy6yqNemqVChgnP58mXvtV46derkt5xe/8b3+i/6f71GjN5ftGhRsw71+uuvm+tV6UXuypYt6wwYMMA5c+aM93oxWgbfm16IUunr68X/PPbv32/2Q/78+Z2CBQua/XP06FHv4/o8vdjezJkzzXOjo6PN9c30Wj0Arg1NS0A2VqBAAXPTPjAJCQmpLn/p0iXT7KRNPd9++61pftLn33777aaWQ33wwQfywgsvyCuvvCK//vqrvPrqq/L888+bGh9fw4cPl2HDhsnPP/8sTZo0kbvuuivVWqAcOXLIk08+Kfv375f169ena1v19bUWRss8depU7/reeOMN2bp1q3n8m2++kaeffto8dsstt5h+MNHR0XLkyBFze+qpp65ab2JionTq1En++usvWblypSxZskT27Nkj3bp181tu9+7dZj9/8cUX5qbLjhkzJl3bACAJ1xiEAFjuk08+MTUrejXeW265xRk5cqSzadOmJGtk3n//fVPDkpiY6H1cr/SbN29ecyVnpVf2nT17tt9rvPTSS6b2xbe2ZcyYMd7HL126ZGpE9MrAKdXIqF9//dU8plflTU+NTIMGDVLdF3PnzjU1Nh561V6teQrkWyPz9ddfOzlz5jQ1VR5bt241Zfzxxx+9NTJa6+NbAzN8+HCncePGqZYJQMqokQGyOe0jc/jwYfnss89MzcqKFSukYcOGpqNroE2bNsmuXbtMjYynNqdIkSJy4cIFU+Nw7tw587Nv377ex/X28ssvm/t9aS2MR2RkpNxwww2mBic1/5et/m80VXo0atQoyT442temTJkyZpseeughUyukfXLSSstcrlw5c/OoVauW6STsuz060klfw6NUqVJy/PjxdG0DgKvR2ReA5MmTR9q2bWtu2gz0yCOPyKhRo6R3795+e+fs2bMmEGjzUVIdYPVx9c4770jjxo39Hs+ZM2dQ9rQnHFSqVMnbPOQJN75NYIHy589/1cioO++804zY0mYwDWSrV682IUybyfLlyyfBlCtXLr/fNYhpsxSAa0ONDICraI2C1q4E0poaHf5cokQJqVKlit8tJiZGSpYsKaVLlzZ9RAIf9wQPj++//977/8uXL5s+LzVr1kzxaOiJX/u06LoaNGjgDVDaf8XXxo0bUz2q+nq6vtdff11uvvlmqVatmqmZ8qV9aq5cuZLierTMBw8eNDePbdu2yalTp8x+BJC5CDJANqbNKK1atZJZs2bJ5s2bZe/evTJ37lwZN26c6cAaqEePHlKsWDHzmHb21eW1KeqJJ56QQ4cOmWVGjx4tcXFxJnDs2LHDDJueNm2ajB8/3m9dkydPlvnz58tvv/1m5oc5efKk9OnT56ryHT161AQjbfpq06aN/Pjjj/Luu+96a3i0/OvWrZOZM2eakKU1SVu2bEl12zVcac3Nm2++adb//vvvezsB+zYHaS2TDkf/448/kmxy0jLVrVvX7JsNGzaY8vXs2VNuu+0201wGIHMRZIBsTPuvaBPQhAkTpHnz5lKnTh3TtPToo4/KW2+9ddXy2tyyatUqM3lely5dTG2ENsVoHxkd3aO0Werf//63CS96gtcTuva3CayR0RE7etN5YbRJR4OKhqTAkKB9SXQ9I0aMMK+ngatly5beZXQUlZZZRxvdeOONcubMGRMkUqOvq+Fq7NixZru1uUwDmC8dudS/f38zAklrfjTgBdImooULF0rhwoXNPtQy63w8c+bMScMRAHCtIrTH7zWvBQDSSPumaKjRYdf169dnvwG4JtTIAAAAaxFkAACAtWhaAgAA1qJGBgAAWIsgAwAArEWQAQAA1iLIAAAAaxFkAACAtQgyAADAWgQZAABgLYIMAACwFkEGAACIrf4flRBQUaRoWH0AAAAASUVORK5CYII=",
      "text/plain": [
       "<Figure size 640x480 with 1 Axes>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "plt.hist(df[\"SleepDuration\"], bins=50)\n",
    "\n",
    "plt.xlabel(\"SleepDuration\")\n",
    "plt.ylabel(\"Frequency\")\n",
    "plt.title(\"Distribution of Sleep duration\")\n",
    "\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f828ed74-8207-4650-84aa-d2d230021f98",
   "metadata": {},
   "source": [
    "Sleep duration is fairly distributed between 5 and 9 hours suggesting that the sample reflects a realistic adult sleeping behaviour rather than outliers like sleep deprivation or oversleeping. This lets us know that the dataset is good for studying NORMAL sleep patterns."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "432922a1-b771-44e4-bad3-4e14a3966351",
   "metadata": {},
   "source": [
    "### Average Sleep Duration by Gender"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "14fabd9d-88fe-4491-aaf3-445c79490eec",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/png": "iVBORw0KGgoAAAANSUhEUgAAAjcAAAHHCAYAAABDUnkqAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjgsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvwVt1zgAAAAlwSFlzAAAPYQAAD2EBqD+naQAARQFJREFUeJzt3Qm4TXX////3Mc9CZMyUMQklU5KhQqYG7krG5hQp7nJHhSQqVEqmdJc03CVKVEihkAyVSJR5noeIsP/X6/P7r/3de5/BOceZ9vJ8XNfi7LXX3uuz1/henzEmEAgEDAAAwCcypXcCAAAAUhLBDQAA8BWCGwAA4CsENwAAwFcIbgAAgK8Q3AAAAF8huAEAAL5CcAMAAHyF4AYAAPgKwQ186a233rKYmBjbuHFjeifFl7p27WplypRJ8/V+8803br9+9NFHdj7TNnjmmWfSbH1btmyxHDly2HfffZdm68zo0uscSO1jZPXq1ZYlSxZbtWqVRTOCmwzo9ddfdwdmnTp10jspGc7Jkyft5Zdftpo1a1q+fPnsggsusEsvvdTuvfde++233yya6MKj/exNuXLlsosvvthat25tkyZNshMnTqRr+rZv3+7SuHLlSjtf/fzzz9atWzcrW7asu7nnyZPHatSoYf/+97/tzz//tPPFoEGD3PWoQYMGYUHm2SYtd747c+aMvf322277FSxY0PLmzWsVK1a0zp072+LFiy2jqVq1qt1444321FNPWTTLkt4JQGzvvvuueyL44YcfbP369XbJJZewmf5/t9xyi82aNctuv/12u+eee+yff/5xQc2MGTOsfv36Vrly5ajbVmPGjHE3TQUz27Ztsy+//NK6d+9uo0aNcr+rVKlS6RbcDBw40B2LuqGHGj9+vLto+5l+4wMPPGAXXnihdezY0R1bp06dck+0ullp/xw/ftwyZ85sfrZnzx7773//6yZPlSpV7J133olz+aNHj9ojjzxiOXPmdDfx813Pnj3ttddes7Zt27rjSLkia9euddexcuXKWd26dS2juf/++61ly5b2xx9/WPny5S0qaeBMZBx//vmnBjINTJ06NVC4cOHAM888k+ZpOH36dOD48eOBjOaHH35w22bIkCGx3jt16lRg7969wdeTJk1yy27YsCGQUT399NMujXv27In13uTJkwOZMmUK1KlTJ8XWp32qfZtYS5cudenTtswo5s2b59L0v//9L1XX89133wUyZ84cuOaaawKHDx+Oc1v279/fHXfpQdtAx09aHBcjRowI5MyZM3DkyJFEfV/Hjh1d+j7++OOAn3Xp0iVQunTpBJfZuXNnICYmJnDPPffEeu/MmTOBXbt2Zchj5OTJk4ECBQoEBgwYEIhWFEtlwFybAgUKuGzBW2+91b32KJdC2ZrKJo90+PBhl23ep0+f4DzlBDz99NMu5yd79uwuB0DZ6ZHFHco+fuihh9y6VMSjZb/44gv33osvvuhyRAoVKuSexK644oo46zvoCVZPKHrKVbZrmzZtXC5EXOW+mq+ciYsuusitS+t88803z7pt9BQhXtZ4KD09K41no6elhg0bWu7cuV06tZ1//fXXWMspN0jbX9tb2/XKK6+0Tz/9NM56PfPnz7f77rvPrV9FZcpuPnDggJ0LPeHdfffdtmTJEps9e3ZwvnJRVNYf6dprr3WTxys2eP/9961///5WokQJV+yl42T//v3uOLnssstcjpHS3KJFC/vpp5/CPl+7dm33t443r5hBvzm++gZ//fWXPfbYY+44036tVKmSO37+33U29vE2bdo0q1atWvAY8I65xDh9+rT95z//saJFi7p9qeNN9UI8Ou6zZs3qch0iqQhTxZl///13vN+vHCulU+eEjpNIOiYGDx4cK9dG+6t58+aWP39+t70bNWoUq56KVxypXFltR6VFy2s7Hzt2LGxZnau9e/e2woULB8+rrVu3xpnmxJxXCR0X8dF+UpGKjpWz0fq0zZTjdfPNN4e9p2K89u3bu3NK61SOxeeffx7rO3bv3m133XWX+x3azpdffnlYrpGoLp1+h44v5YooB0Tfef3117vjQMec9k/JkiXddUu5Jjruk3s98I5VpUf/f/LJJ5YYGzZscGmJ65ql9BcpUiRs3sGDB93+1rmlfaj063qyd+/eYLG8iot0HdYxo3Qr/fPmzUtUerYl8tqrc0fXk+nTp1vUSu/oCuEqV64cuOuuu9zf8+fPd9G3ciw83bt3D1xwwQWBEydOhH3uv//9r1tWT9uiJ7Hrr78+kCtXrsAjjzwSGDt2bOChhx4KZMmSJdC2bduwz+pzVapUcTlFAwcODLz22muBFStWuPdKliwZePDBBwOjR492T3BXXXWVW37GjBlh39GhQwc3v1OnTu7zen355ZfH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AABIy2Kpf/3rX3bs2DE3nlSuXLksa9asYe/v37//XNIDAACQtsGNcm6AaEA/GABwfkpycNOlS5fUSQmQwugHAwDOT8nqxO/06dM2bdo0W7NmjXt96aWXWps2bejnBgAARF9ws379emvZsqVt27bNKlWq5OYNHTrUtaL6/PPPXV0cAACAqGkt1bNnTxfAbNmyxZYvX+4mdepXtmxZ9x4AAEBU5dx8++23tnjxYitYsGBwXqFChez555+3Bg0apHT6AAAAUjfnJnv27HbkyJFY848ePWrZsmVL6tcBAACkb3DTqlUru/fee23JkiWuqa0m5eTcf//9rlIxAABAVAU3r7zyiqtzU69ePcuRI4ebVBx1ySWX0AcOAACIvjo3F1xwgU2fPt21mvKaglepUsUFNwAAAFGXczNo0CA3/IKCmdatW7tJfx8/fty9BwAAEFXBzcCBA13l4UgKePQeAABAVAU3qkAcExMTa/5PP/0U1jwcAAAgQ9e5KVCggAtqNFWsWDEswNFwDMrNUYspAACAqAhuNBq4cm26d+/uip/y588ffE/925QpU8a1oAIAAIiK4MYbDVzDLNSvX9+yZs2amukCAABIm6bgjRo1Cv79999/28mTJ8Pez5cvX/JSAgAAkB4VitUq6qGHHrIiRYpY7ty5XV2c0AkAACCqgpu+ffva119/bWPGjHHjTE2YMMHVwSlevLi9/fbbqZNKAACA1CqW+uyzz1wQc+2111q3bt2sYcOGrhO/0qVL27vvvmsdO3ZM6lcCAACkX87N/v37rVy5csH6NXotV199tc2fPz/lUgYAAJAWwY0Cmw0bNri/K1eubB9++GEwR0fjTgEAAERVcKOiKPVGLE888YS99tprbmTw3r17u/o4AAAAUVXnRkGMp1mzZvbbb7/ZsmXLXL2b6tWrp3T6AAAAUi/n5p9//rGmTZvaunXrgvNUkfjmm28msAEAANEX3KhX4p9//jn1UgMAAJDWdW7uvPNOmzhx4rmuFwAAIGPUuTl16pS9+eabNmfOHLviiitcL8WhRowYkZLpAwAASN3gZtWqVVarVi339++//x72XkxMTFK/DgAAIH2Dm3nz5qVsCgAAANIzuAGA890VfRlHL73FnDpp+UNeXzvgfQtkyZaOKYIse6GzRWVw07hx4wSLnzSoJgAAQNQENzVq1IjV983KlStdXZwuXbqkZNoAAABSP7gZOXJknPOfeeYZO3r0aNJTAAAAkJ793CTU/42aiAMAAPgiuFm0aJEbQBMAACCqiqU0jlSoQCBgO3bssB9//NEGDBiQkmkDAABI/eAmf/7QxndmmTJlskqVKtmgQYPs+uuvT3oKAAAA0jO4mTRpUkquHwAAIH2DGxVDLVu2zDZu3Oj6uylXrpxrHs7QC+Ho5Cv90clXxpRROvkC4F9Zkjr0wl133WWbNm1yQY4oqClbtqxrKXXNNdekVjoBAABStrXU+vXrrVWrVlamTBmbOnWqrVmzxlavXm3/+9//rGTJktayZUv7888/LSn0XQqOIqcePXrE+xmtr3Llyq5l1mWXXWYzZ85M0joBAIC/JTq4GTVqlNWtW9cNr9C2bVtXiVhBhlpPKUenTp068XbwF5+lS5e6llbeNHv2bDe/ffv2cS7//fff2+233+5yj1asWGHt2rVzk3pHBgAASFJw880339gjjzwS53vKbdF7SR0xvHDhwla0aNHgNGPGDCtfvrw1atQozuVffvlla968ufXt29eqVKligwcPtlq1atno0aPZmwAAIGnBzebNm10xUHyqVavm6uIk18mTJ23y5MnWvXv3eCsnq6PAZs2ahc274YYb3Pz4nDhxwg4fPhw2AQAA/0p0cKNxo3LlyhXv+3rv2LFjyU7ItGnT7ODBg9a1a9d4l9m5c6dddNFFYfP0WvPjM3ToUNc3jzeVKlUq2WkEAAA+ay2lCsTxBRJ79+49p4RMnDjRWrRoYcWLF7eU1K9fP3v00UeDr5VzQ4ADAIB/JSm4adq0abAJeCgVI2l+cvu6UXHWnDlzXCushKhezq5du8Lm6bXmxyd79uxuAgAA54dEBzcbNmxItUSo1+MiRYrYjTfemOBy9erVs7lz54ZVbFYLK80HAABIUnBTunTpVNliZ86cccFNly5dLEuW8OR07tzZSpQo4erNSK9evVxLqpdeeskFQu+//74bsHPcuHGpkjYAAODjCsWpRcVRaomlVlKRNF/933jq169vU6ZMccHM5Zdfbh999JGriKyWWgAAAMkaWyqlaSTxuOrxeH3rRFIHf/F18gcAAJDuOTcAAAApieAGAAD4SrKLpXbv3m1r1651f2ucKbV2AgAAiLqcmyNHjlinTp1cKya1XNKkv++88047dOhQ6qQSAAAgtYKbu+++25YsWeIGudRwCZr0t5pk33fffUn9OgAAgPQtllIg8+WXX9rVV18dNnjl+PHj3YjdAAAAUZVzU6hQITcAZSTNK1CgQEqlCwAAIG2Cm/79+7uBKEMH0NTfffv2tQEDBrAbAABAdBVLjRkzxtavX28XX3yxm7yehDU45Z49e2zs2LHBZZcvX56yqQUAAEjp4KZdu3ZJ/QgAAEDGDW6efvrp1EkJAABAevVQrObfEyZMsH79+tn+/fuDRVDbtm1LiTQBAACkXc7Nzz//bM2aNXOtozZu3Gj33HOPFSxY0KZOnerq3rz99tvJTw0AAEBa59yopVTXrl1t3bp1liNHjuD8li1b2vz58881PQAAAGkb3CxdujTOnog1BENo83AAAICoCG7U5Pvw4cOx5v/+++9WuHDhlEoXAABA2gQ3bdq0sUGDBtk///zjXsfExLi6No8//rjdcsstyUsFAABAegU3L730kh09etSKFClix48fd6OCX3LJJZY3b14bMmRISqULAIB4BTJntUPVbw9Oeg0ku7WUWknNnj3bFi5c6FpOKdCpVauWa0EFAECaiImxQJZsbGykTHDj0ajgV155pauDo6IpAACAqCyWOnPmjA0ePNi1jsqTJ49t2LDBzdegmRMnTkyNNAIAAKRecPPss8/aW2+9ZcOHD7ds2f4vS7BatWqu12IAAICoCm7UA/G4ceOsY8eOljlz5uD8yy+/3H777beUTh8AAEDqBjcaP0qto+IqrvKahwMAAERNcFO1alVbsGBBrPkfffSR1axZM6XSBQAAkDatpZ566inr0qWLy8FRbo0GzFy7dq0rrpoxY0byUgEAAJBeOTdt27a1zz77zObMmWO5c+d2wc6aNWvcvOuuuy6l0gUAAJB2/dw0bNjQdeQHREMPpqGvAQD+l+xO/IAMjx5MAeC8lKjgpkCBAonuhXj//v3nmiYAAIDUDW5GjRqV/DUAAABktOBGraMAAAB8Vefm1KlTdvr0aTdQpmfXrl32xhtv2F9//WVt2rRxg2kCAABERXBzzz33uLGkxo4d614fOXLEateubX///bcVK1bMRo4cadOnT7eWLVumZnoBAABSpp+b7777zm655Zbga3Xap5ycdevW2U8//WSPPvqovfDCC4n9OgAAgPQNbtQjcYUKFYKv586d64Kd/PnzB+vl/Prrr6mTSgAAgJQObnLkyGHH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0qjbCm4efvjh5KUCAAAgvYIb5dY8+eST1rdvX1c8dfToUatatarlyZMnpdIEAACQdsVSkydPdjk22bJlc0GNRuMmsAEAAFEb3PTu3duKFClid9xxh82cOZOxpAAAQHQHNzt27LD333/fFU916NDBihUrZj169LDvv/8+dVIIAACQmsFNlixZrFWrVq6F1O7du23kyJG2ceNGa9y4sZUvXz6pXwcAAJC+FYpD5cqVyw3FcODAAdu0aZOtWbMm5VIGAACQVgNnqkKxcm5atmxpJUqUsFGjRtlNN91kv/76a3K+DgAAIP1ybm677TabMWOGy7VRnZsBAwZYvXr1Ui5FAAAAaRncZM6c2T788ENXHKW/Q61atcqqVat2LukBAABI2+BGxVGhjhw5Yu+9955NmDDBli1bRtNwAAAQfXVuZP78+dalSxfXFPzFF1+0Jk2a2OLFi1M2dQAAAKmZc7Nz50576623bOLEiXb48GFX5+bEiRM2bdo011sxAABA1OTctG7d2ipVqmQ///yzax2l0cBfffXV1E0dAABAauXczJo1y3r27GkPPPCAVahQIanrAQAAyFg5NwsXLnSVh6+44gqrU6eOjR492vbu3Zu6qQMAAEit4KZu3bo2fvx4N7bUfffd58aXKl68uJ05c8Zmz57tAh8AAICoay2VO3du6969u8vJ+eWXX+yxxx6z559/3o0U3qZNm9RJJQAAQGo3BRdVMB4+fLht3brV9XUDAAAQ1cGNRz0Vt2vXzj799NOU+DoAAID0DW4AAAAyCoIbAADgKwQ3AADAVwhuAACArxDcAAAAXyG4AQAAvkJwAwAAfIXgBgAA+ArBDQAA8BWCGwAA4CsENwAAwFcIbgAAgK8Q3AAAAF8huAEAAL5CcAMAAHyF4AYAAPgKwQ0AAPAVghsAAOArBDcAAMBXCG4AAICvENwAAABfIbgBAAC+QnADAAB8heAGAAD4CsENAADwFYIbAADgKwQ3AADAVwhuAACArxDcAAAAXyG4AQAAvkJwAwAAfIXgBgAA+ArBDQAA8JV0D262bdtmd955pxUqVMhy5sxpl112mf34448JfubEiRP25JNPWunSpS179uxWpkwZe/PNN9MszQAAIOPKkp4rP3DggDVo0MAaN25ss2bNssKFC9u6deusQIECCX6uQ4cOtmvXLps4caJdcskltmPHDjtz5kyapRsAAGRc6RrcDBs2zEqVKmWTJk0KzitbtmyCn/niiy/s22+/tT///NMKFizo5innBgAAIN2LpT799FO78sorrX379lakSBGrWbOmjR8/PlGfGT58uJUoUcIqVqxoffr0sePHj6dZugEAQMaVrjk3yn0ZM2aMPfroo/af//zHli5daj179rRs2bJZly5d4v3MwoULLUeOHPbJJ5/Y3r177cEHH7R9+/aF5QCF1s/R5Dl8+HCq/iYAAHAeBzeqJ6NcmOeee869Vs7NqlWr7I033og3uNFnYmJi7N1337X8+fO7eSNGjLBbb73VXn/9dVcpOdTQoUNt4MCBafBrAACAne/FUsWKFbOqVauGzatSpYpt3rw5wc+oOMoLbLzPBAIB27p1a6zl+/XrZ4cOHQpOW7ZsSeFfAQAAMpJ0DW7UUmrt2rVh837//XfXxDuhz2zfvt2OHj0a9plMmTJZyZIlYy2vpuL58uULmwAAgH+la3DTu3dvW7x4sSuWWr9+vU2ZMsXGjRtnPXr0CMt56dy5c/D1HXfc4frE6datm61evdrmz59vffv2te7du8cqkgIAAOefdA1uateu7SoFv/fee1atWjUbPHiwjRo1yjp27BhcRn3YhBZT5cmTx2bPnm0HDx509XW0bOvWre2VV15Jp18BAAAyknStUCytWrVyU3zeeuutWPMqV67sAhwAAIAMN/wCAABASiK4AQAAvkJwAwAAfIXgBgAA+ArBDQAA8BWCGwAA4CsENwAAwFcIbgAAgK8Q3AAAAF8huAEAAL5CcAMAAHyF4AYAAPgKwQ0AAPAVghsAAOArBDcAAMBXCG4AAICvENwAAABfIbgBAAC+QnADAAB8heAGAAD4CsENAADwFYIbAADgKwQ3AADAVwhuAACArxDcAAAAXyG4AQAAvkJwAwAAfIXgBgAA+ArBDQAA8BWCGwAA4CtZ7DwTCATc/4cPH07V9Zw+cTxVvx+IVql97qUFzm8g7c9v77u9+3hCYgKJWcpHtm7daqVKlUrvZAAAgGTYsmWLlSxZMsFlzrvg5syZM7Z9+3bLmzevxcTEpHdykMoU6SuY1cmQL18+tjfgI5zf55dAIGBHjhyx4sWLW6ZMCdeqOe+KpbRBzhbxwX8U2BDcAP7E+X3+yJ8/f6KWo0IxAADwFYIbAADgKwQ38LXs2bPb008/7f4H4C+c34jPeVehGAAA+Bs5NwAAwFcIbgAAgK8Q3AAAAF8huAHiUaZMGRs1ahTbB4giGzdudB20rly5Mr2TgnREcIMMoWvXru6CFDmtX78+vZMGII3O//vvvz/Wez169HDvaRkgsQhukGE0b97cduzYETaVLVs2vZMFIA1omJT333/fjh//v0GH//77b5syZYpdfPHF7AMkCcENMlSfFUWLFg2bMmfObNOnT7datWpZjhw5rFy5cjZw4EA7depU8HN6qhs7dqy1atXKcuXKZVWqVLFFixa5XJ9rr73WcufObfXr17c//vgj+Bn93bZtW7vooossT548Vrt2bZszZ06C6Tt48KDdfffdVrhwYdfde5MmTeynn35K1W0CnC90jivAmTp1anCe/lZgU7NmzeC8L774wq6++mq74IILrFChQu68Dz2347Jq1Spr0aKFO9d1znfq1Mn27t2bqr8H6YvgBhnaggULrHPnztarVy9bvXq1C2LeeustGzJkSNhygwcPdsupnL1y5cp2xx132H333Wf9+vWzH3/80Q249tBDDwWXP3r0qLVs2dLmzp1rK1ascLlGrVu3ts2bN8eblvbt29vu3btt1qxZtmzZMncxbtq0qe3fvz9VtwFwvujevbtNmjQp+PrNN9+0bt26hS3z119/2aOPPurOa52/Gi/wpptucoMix/dQogcRBUj6jIKjXbt2WYcOHVL99yAdqRM/IL116dIlkDlz5kDu3LmD06233hpo2rRp4Lnnngtb9p133gkUK1Ys+FqHcf/+/YOvFy1a5OZNnDgxOO+9994L5MiRI8E0XHrppYFXX301+Lp06dKBkSNHur8XLFgQyJcvX+Dvv/8O+0z58uUDY8eOPYdfDkDnf9u2bQO7d+8OZM+ePbBx40Y36Zzds2ePe0/LxEXv63z/5Zdf3OsNGza41ytWrHCvBw8eHLj++uvDPrNlyxa3zNq1a9n4PnXejQqOjKtx48Y2ZsyY4GsVJ1WvXt2+++67sJya06dPu7L4Y8eOuWIo0XIeZTvLZZddFjZPnzl8+LArUlLOzTPPPGOff/65q9ujYi6V9ceXc6PiJ31G2eCh9JmzZYkDSBwV+d54440ud1bPLfr7wgsvDFtm3bp19tRTT9mSJUtc0ZKXY6Nzt1q1anGeu/PmzXNFUpF07lasWJHd40MEN8gwFMxccsklYfMUUKiO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",
      "text/plain": [
       "<Figure size 640x480 with 1 Axes>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "sns.barplot(\n",
    "    data=df,\n",
    "    x=\"Gender\",\n",
    "    y=\"SleepDuration\"\n",
    ")\n",
    "\n",
    "plt.ylim(6.5,7.5) #this changes the rnage of the y axis, allowing for a more zoomed visual\n",
    "\n",
    "plt.title(\"Average Sleep Duration by Gender (Zoomed Scale)\")\n",
    "plt.ylabel(\"Average Sleep Duraton (hours)\")\n",
    "\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5174a356-6cdc-400f-963c-61f2270b3eb0",
   "metadata": {},
   "source": [
    "The graph shows that males and females have very similar average sleep durations, with males only being slightly more. The lack of difference between these two demographics suggests that there may be other factors that contribute to higher quality sleep and duration."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "be4ee2a3-d5bc-47c1-b00b-3e973a128c08",
   "metadata": {},
   "source": [
    "### Caffeine Consumption vs Sleep Duration"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "58c55e62-f3e6-40bb-9291-58604c8949d3",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/png": "iVBORw0KGgoAAAANSUhEUgAAAjcAAAHHCAYAAABDUnkqAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjgsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvwVt1zgAAAAlwSFlzAAAPYQAAD2EBqD+naQAASzxJREFUeJzt3QncTOX///GPfd+3KCEpu4gkyVeRSkULfS2hlEgRpVLZUpZCWvlSobKUorSgqLQRQiVl3xJpsUbW83+8r99/5jFz33PfZm73fc99H6/n43Hc5sw5Z645c51zPuc615LF8zzPAAAAfCJrvBMAAACQmghuAACArxDcAAAAXyG4AQAAvkJwAwAAfIXgBgAA+ArBDQAA8BWCGwAA4CsENwAAwFcIbjKAp59+2s455xzLli2bXXDBBW7esWPH7MEHH7SyZcta1qxZrVWrVjFt8z//+Y+bkPkNGjTIsmTJYqezzp07W/ny5eOdDN/SvtU+jpennnrKKleubCdOnIhbGjIaHfM69jOiSZMmufRt3rw55nUffvhhq1+/vqU1gpsYbdiwwe666y4XjOTOndsKFixoDRs2tGeffdYOHToU8w/w8ccfuyBG25g4caINHTrUzX/11Vdd0HPzzTfb5MmTrXfv3paZ7Nu3zwYPHmy1atWy/PnzW548eax69er20EMP2W+//Rbv5GU4Bw8edCeyzz//3E4nf/zxh/Xq1ctd2JRHSpYsaRdddJHLJwcOHLDMRDcTOuFr0g2Jzg3nn3++3XrrrfbJJ5/EO3n2zTffuDy2Z88ey2jnihEjRrjfXPtNFGgF9mVSE8Fu5jyG7rvvPvv+++9t9uzZafo52dN06z7z4YcfWuvWrS1XrlzWsWNHd7E+cuSIffXVV9a3b1/76aefbPz48TFt89NPP3UH9CuvvGI5c+YMm3/mmWfaM888k6K0KmiKl40bN1rTpk1t69atbn917drVfbcffvjBfc9Zs2bZ2rVr45a+jBrcKBiUhCVujz32mLvb8Zu///7b6tat6y5ut99+uzs5//XXXy6fjB071rp37+4C48zkrLPOsmHDhrn///PPP7Z+/XqbOXOmvfHGG9amTRv3N0eOHHELbpTHFDgULlw47L01a9YEA4v0phs5lVS3bds2OE83kDqHRLJgwQJXcnDxxRfb6S4zHkNnnHGGtWzZ0kaOHGnXX399mn0OwU2UNm3aZP/973+tXLlyLvAoXbp08L0ePXq4k5iCn1jt2rXLRduhgU1gfsITUCwSbi+96CR144032u+//+5KIS699NKw95988kl3l4boZc+e3U1+o0BXAfDXX39tl1xySdh7OlnHKw+fikKFClmHDh3C5g0fPtx69uxpL730kittSK38r+ApX758qbIt3bDFi0qsdZFTSXhAgwYN3JTQjh07rE+fPu48rIv36S6zHkNt2rRxN766EdZTkDShUcFxct26ddPo6d7XX38d1e569dVXvSZNmnglSpTwcubM6VWpUsV76aWXwpbR9hJOEydOjDj/s88+c+scP37ce+aZZ7yqVat6uXLl8kqWLOl17drV+/vvv8O23bhxYzcFaH1t58033/SeeOIJ78wzz3TrX3755d66desSpX/x4sVe8+bNvYIFC3p58uTxLrvsMu+rr7466feePn26+5wnn3zSi9Zbb73l1alTx8udO7dXrFgxr3379t6vv/4atkynTp28fPnyufktW7Z0/y9evLh3//33e8eOHQtbdtq0aW57+fPn9woUKOBVr17dGzNmTPD9gQMHujQmFNj3mzZtCs4rV66c16JFC7f/LrzwQpdGbS/we7zzzjvutfalPnP58uUR071hwwbvyiuv9PLmzeuVLl3aGzx4sHfixAm3jD4v0m+udCaV3qNHj3qPP/64d84557j8pXT269fP+/fff8OWC6T/yy+/9OrVq+fSWaFCBW/y5MnJ/iZHjhzxihQp4nXu3DnRe3v37nXb0b4PeO6551yeVF4pXLiw21dTpkxJ9jPuuusuL1u2bC5Pn4z2o75LqGiPBfnoo4+8Sy+91O1/5YtrrrnGW7VqVcy/VXJ0vFWrVi3ie8qjSqe2uWfPnrDfXfkuodDfPzQP/PTTT17btm3dPr7gggvce99//71Lu35X7YdSpUp5t912m/fnn38mWj/hFMjr2rfaRijth5tvvtnlA/2u9evX9z744IOwZWI9ryS0ceNGt/6kSZNOuqx+b51Ts2fPHvE8HM15RBYsWBDMC4UKFfKuv/56b/Xq1WHLBPbXmjVr3HZ0HtT55rHHHnN5YevWrW49nV+0v0eOHJnoc3QsDhgwwKtYsaI7Rs866yyvb9++iY5Rvb7vvvvc9pU3r7vuOm/btm2J8sCpHkOB8/rVV1/t8o++f40a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LpsrVy43AQCA00OGCG4mTpxoJUuWtBYtWpx02aeeesqefPJJmzdvntWtWzdd0gcAADKPuD+WOnHihAtuOnXqZNmzh8daagGlx0oBavrdv39/e/XVV10fOTt37nST+lkBAADIEMGNHi1t3brVbr/99kTvaf6OHTuCr8eOHetaVd18881WunTp4KTHVAAAABnisZQ64Uuqd1t12hdq8+bN6ZQqAACQWcW95AYAACA1EdwAAABfIbgBAAC+Evc6NwAA+JXqlGqg4YB8+fJFPcQQUo7gBgCANKLApmXLlsHX7733nuXPn5/9ncZ4LAUAAHyF4AYAAPgKwQ0AAPAVghsAAOArBDcAAMBXCG4AAICvENwAAABfIbgBAAC+QnADAAB8heAGAAD4CsENAADwFcaWAuALDFAIIIDgBoAvMEAhgAAeSwEAAF8huAEAAL5CcAMAAHyF4AYAAPgKwQ0AAPAVghsAAOArBDcAAMBXCG4AAICvENwAAABfSVEPxVu3brUtW7bYwYMHrUSJElatWjXLlStX6qcOAAAgrYKbzZs329ixY2369On266+/unFcAnLmzGmNGjWyrl272k033WRZs1IgBAAAMnBw07NnT5s8ebI1b97cnnjiCbvooousTJkylidPHvv7779t1apV9uWXX9qAAQNs8ODBNnHiRKtXr5752YV9X7PTWZZjR6xQyOv/9J9uXvacdrr67umO8U4CACCW4CZfvny2ceNGK1asWKL3SpYsaZdffrmbBg4caHPnzrVt27b5PrgBAACZOLgZNmxY1Bu86qqrTiU9AAAApyTmyjGHDh1yFYkDVLF4zJgxNm/evFNLCQAAQDyCm5YtW9prr/1ffZM9e/ZY/fr1bdSoUdaqVStX4RgAACBTBTfLly93LaPk7bfftlKlSrnSGwU8zz33XFqkEQAAIO2CGz2SKlCggPv/xx9/bDfeeKNr+n3xxRe7IAcAACBTBTfnnnuuvfvuu65FlOrZXHnllW7+rl27rGDBgmmRRgAAgLQLbtSXzQMPPGDly5d39W0aNGgQLMWpXbt2rJsDAACI7/ALN998s1166aW2Y8cOq1WrVnD+FVdcYTfccENM21KAFOlR1t13320vvvhixHVmzJhh/fv3dz0mV6pUyUaMGGHXXHNNrF8DAJAO6PCUDk/j0eFpTCU3R48etezZs9uff/7pSmlCh1lQr8WVK1eO6cOXLl3qgqTA9Mknn7j5rVu3jrj8N998Y23btrUuXbrYihUrXAstTeohGQAAIObgJkeOHHb22Wfb8ePHU2XvadDNM844Izh98MEHVrFiRWvcuHHE5Z999lnXSWDfvn2tSpUqNmTIEKtTp4698MIL/JoAACBldW4effRRe+SRR9yYUqnpyJEj9sYbb9jtt99uWbJkibjMokWLrGnTpmHzNN6V5ifl8OHDtm/fvrAJAAD4V8x1blRKsn79ejdwZrly5dy4Uwn7wUkJtcBSp4CdO3dOcpmdO3e6fnVC6bXmJzd0hAbzBAAAp4eYgxvVcUkLr7zyil199dUuaEpN/fr1sz59+gRfq+SmbNmyqfoZAAAgEwc3Gvk7tanF1Pz5823mzJnJLqd6Ob///nvYPL3W/KTkypXLTQAA4PQQc52btDBx4kQrWbKktWjRItnl1KfOggULwuaphVWgrx0AAICYS27U/DupCr8Sa0uqEydOuOCmU6dOrpl5qI4dO9qZZ57p6s1Ir169XEsqDdSpQGj69Om2bNkyGz9+PL8kAABIWXAza9asRH3fqM+ZyZMnp6jirh5Hbd261bWSSkjzQ/vSueSSS2zq1Kn22GOPuRZb6sRPFZGrV68e8+cCfkNnaXSWFq8O04BMH9y0bNkyYq/F1apVszfffNN1sBcLjU3leV7E9z7//PNE89TBX1Kd/AEAAKRanRuNCp6wPgwAAECmDG4OHTpkzz33nKsfAwAAkKkeSxUpUiSsQrEeKe3fv9/y5s3rehgGAADIVMHNmDFjwl6rwq/GiKpfv74LfAAAADJVcKMm2wAAAL4JbkRjQGm4hJ9//tm9VkspNeUuVKhQaqcPAAAgbSsUq9O8ihUr2jPPPONGBtc0evRoNy+lg2YCAADEreSmd+/edv3119uECROCPQofO3bM7rjjDrvvvvvsiy++SLXEAQAApHlwo5Kb0MDGbSR7dnvwwQetbt26MScAAAAgro+lChYs6IZFSGjbtm1WoECB1EoXAABA+gQ3t9xyixtiQUMtKKDRpAEs9Viqbdu2KUsFAABAvB5LjRw50nXipxG7VddGcuTIYd27d7fhw4enVroAAADSJ7jJmTOnPfvsszZs2DDbsGGDm6eWUuqhGAAAIFP2cyMKZmrUqJG6qQEAAEjv4Oaff/5xj580AviuXbvsxIkTYe9v3LjxVNMEAACQfsGNKg4vXLjQbr31VitdunTYIJoAAACZLriZM2eOffjhh9awYcO0SREyBS9bDttbs23YawAAMmVwo5G/ixYtmjapQeaRJYt52XPGOxUAAJx6PzdDhgyxAQMG2MGDB2NdFQAAIGOU3NSuXTusbs369eutVKlSVr58edfHTSgGzwQAABk+uGnVqlXapwQAACC9gpuBAwemxmcBAABkjDo3nuelfUoAAADSK7ipVq2aGxzzyJEjyS63bt06xpgCAAAZ/7HU888/bw899JDdfffd1qxZM6tbt66VKVPGcufObbt377bVq1fbV199ZT/99JPdc889LsABAOB0R59gGTi4ueKKK2zZsmUugHnzzTdtypQptmXLFjt06JAVL17ctabSKOHt27d3/eAAAAD6BMsUnfhdeumlbgIAAPBNJ34AAAAZGcENAADwFYIbAADgKwQ3AADAVwhuAADA6dtaKuDEiRNu8Mxdu3a5/4e67LLLUittAAAAaR/cLF682Nq1a+f6uUk4LINGDj9+/HjsqQAAAIhXcNOtWzfXQ/GHH35opUuXdgENAABApg1uNH7U22+/beeee27apAgAACA9KxTXr1/f1bcBAADwRcnNvffea/fff7/t3LnTatSoYTly5Ah7v2bNmqmZPgCICgMUAkhxyc1NN91kP//8s91+++1Wr149u+CCC9zAmYG/sdq+fbt16NDBihUrZnny5HEBkwbpTI4G7qxVq5blzZvX1ftRWv7666+YPxuAj2TJYl72nMFJrwGcnmIuudm0aVOqffju3butYcOG1qRJE5szZ46VKFHC1elJbmTxr7/+2o1A/swzz9h1113ngiNVcr7zzjtt5syZqZY2AABwmgQ35cqVS7UPHzFihJUtW9YmTpwYnFehQoVk11m0aJGVL1/eevbsGVz+rrvuctsCAABIUQ/FGzZscHVvmjZt6iYFGpoXq9mzZ7tm5a1bt7aSJUu6x1oTJkxIdp0GDRrYtm3b7KOPPnL97Pz++++u9dY111zDrwkAAGIPbubNm2dVq1a1JUuWuMrDmr799lurVq2affLJJzFta+PGjTZ27FirVKmS22737t1doDR58uQk19FjLNW5ueWWWyxnzpx2xhlnWKFChezFF1+MuPzhw4dt3759YRMAAPCvmIObhx9+2Hr37u0CmtGjR7tJ/7/vvvvsoYceimlbGrqhTp06NnToUFdq07VrV1d3Zty4cUmus3r1auvVq5cNGDDAvvvuO5s7d65t3rzZ1buJZNiwYS74CUx6DAYAAPwr5uBGLaW6dOmSaL5aLCnwiIVaOqkUKFSVKlVs69atSa6jYEWlN3379nWlRs2bN7eXXnrJXn31VduxY0ei5fv162d79+4NTnqkBQAA/CvmCsVq0bRy5Ur3KCmU5qneTCwUpKxZsyZs3tq1a5OttHzw4EHLnj082dmyZXN/E451Jbly5XITAAA4PcQc3OixkR4fqb7MJZdcEmyerdZKffr0iWlberylbeixVJs2bVw9nvHjx7sptORFzb1fe+0191rNv5UG1dVRqY1Ka/RI7KKLLrIyZcrE+nUAAMDpHtz079/fChQoYKNGjXKBhyioGDRoULB5drTUCeCsWbPcdh5//HHXrHvMmDHWvn374DIKXkIfU3Xu3Nn2799vL7zwguspuXDhwnb55ZfTFBwAADhZvEjPcqKkIEMU7GQWai2lisWqf1OwYMEUb+fCvv9XkgTId093jPuOIE8iIfIl/JQnY7l+x1xyEyozBTUAAOD0EFVwo+baCxYscMMiqMl2lmTGbFm+fHlqpg8AACD1g5uWLVsGWxzp/8kFNwAAABk+uBk4cGDw/6o4DAAA4JtO/M455xz766+/Es3fs2ePew8AACBTBTca6uD48eMRx3D69ddfUytdAAAAKZI9lhG8AzTIpZpjBSjYUYVj9VMDAACQKYKbVq1aub+qTNypU6ew93LkyGHly5d3HfsBAABkiuBGI3iLSmeWLl1qxYsXT8t0AQAApEjMnfht2rQpZZ8EAACQDlLUQ/E///xjCxcudGM+HTlyJOy9WMeXAgAAiGtws2LFCrvmmmvs4MGDLsgpWrSo/fnnn5Y3b14rWbIkwQ0AAMhcTcF79+5t1113ne3evdvy5Mljixcvti1bttiFF15oI0eOTJtUAgAApFVws3LlSrv//vsta9asli1bNte/TdmyZe2pp56yRx55JNbNAQAAxDe4UbNvBTaix1CqdyPq92bbtm2pmzoAAIC0rnOjUcHVFLxSpUrWuHFjGzBggKtz8/rrr1v16tVj3RwAAEB8S26GDh1qpUuXdv9/8sknrUiRIta9e3f7448/bPz48ambOgAAgLQsufE8zz2KCpTQ6P9z586N9TMBAAAyRsmNgptzzz2XujUAAMAfwY0qEquuzV9//ZV2KQIAAEjPOjfDhw+3vn372qpVq9jxAAAg87eW6tixo+uduFatWpYzZ07XkV+ov//+OzXTBwAAkLbBzZgxY2JdBQAAIOMGN506dUqblAAAAMQjuAn0SJyUs88++1TSAwAAkL7BTfny5S1LlixJvn/8+PFTSxEAAEB6BjcrVqwIe3306FE3b/To0a7HYgAAgEwV3KiVVEJ169a1MmXK2NNPP2033nhjaqUNAAAg7fu5Scr555/vBtQEAADIVCU3+/btSzQkw44dO2zQoEGu92IAAIBMFdwULlw4UYViBThly5a16dOnp2baAAAA0j64+eyzzxKNN1WiRAk3oGb27DFvDgAAIFXFHI00btw4dVMAAAAQz+Dm008/tZkzZ9rmzZvd46kKFSrYzTffbJdddllqpgsAACDtW0t169bNmjZtatOmTbO//vrL/vjjD5syZYo1adLE7r333pSlAAAAIB7BzaxZs2zixIn26quv2p9//mmLFi2yxYsXuwBnwoQJNn78eJs9e3Zqpg0AACDtghsFNn369LHOnTuHtZZSheLbb7/d7rvvPnvllVdiTwEAAEA8gpvly5fbDTfckOT76pn4u+++S610AQAApG1wo0dRZ511VpLv6z3VwwEAAMgUwc2RI0csR44cSb6vPm60TKy2b99uHTp0sGLFilmePHmsRo0atmzZsmTXOXz4sD366KNWrlw5y5UrlxupXHWBAAAAYmoK3r9/f8ubN2/E9w4ePBjz3ty9e7c1bNjQtbaaM2eO6wxw3bp1VqRIkWTXa9Omjf3++++ujo86D9TwDydOnIj58wEAwGkc3KgfmzVr1px0mViMGDHCDdugysoB6jcnOXPnzrWFCxfaxo0brWjRom6eSm4AAABiCm4+//zzVN9jajrevHlza926tQtYzjzzTLv77rvtzjvvTHadunXr2lNPPWWvv/665cuXz66//nobMmSIe6wV6RGWpqQG/gQAAKdxJ36pTaUvY8eOdaOJz5s3z7p37249e/a0yZMnJ7vOV199ZatWrXJ974wZM8befvttFxRFMmzYMCtUqFBwUkkRAADwr7gGN6onU6dOHRs6dKjVrl3bunbt6kptxo0bl+w66mdHPSNfdNFFds0119jo0aNdQHTo0KFEy/fr18/27t0bnLZt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J2uyrcBm1qxZ9umnn1qFChVOusNWrlzp/qoEJxJtQxeU0Hy6b98+12qKfIpYHThwwJUSKr/pfJkjR46wvKVHpKqTk1TeIj+moTSsrIxMbvr06a4VyaRJk7zVq1d7Xbt29QoXLuzt3LnTvX/rrbd6Dz/8cHD5r7/+2suePbs3cuRI10pALQvUeuDHH3+M47dAZtW9e3evUKFC3ueff+7t2LEjOB08eNC9v379eu/xxx/3li1b5m3atMl77733vHPOOce77LLLwrZz/vnnezNnzgy+Hj58uMvHWv6HH37wWrZs6VWoUME7dOhQun9HZC7333+/y4/KbzrfNW3a1CtevLhrySfdunXzzj77bO/TTz91+bJBgwZuCkV+TB8EN0jW888/7w7WnDlzuqbhixcvDmuG26lTp7Dl33rrLe+8885zy1erVs378MMP2cNI2cnJLOI0ceJE9/7WrVtdIFO0aFEXhJ977rle3759vb179ybaTmCdQPPb/v37e6VKlXLrXXHFFd6aNWv4lXBSt9xyi1e6dGl3fjvzzDPdawXZAQqQ7777bq9IkSJe3rx5vRtuuMEF5OTH9JdF/6RlyRAAAEB6os4NAADwFYIbAADgKwQ3AADAVwhuAACArxDcAAAAXyG4AQAAvkJwAwAAfIXgBsjg3n33XTv33HPdWF8aGTupeSdTvnx5GzNmTBqnFknp3LmztWrVKl120CuvvGJXXnllmn/O6tWr3Xhf//zzT5p/FhALOvED0sjOnTvtySeftA8//NC2b99uJUuWtAsuuMAFIxq5OlqlSpWy2267zXr27GkFChRwU6R5J/PHH39Yvnz5LG/evJaW1C/ohAkT3AX2p59+suzZs7tArEOHDm4U77T+/HjbvHmzGzNoxYoV7vcO2Lt3r9s3GmwxLf377792zjnn2IwZM6xhw4aW1m6++WarVauW9e/fP80/C4gWJTdAGl3gNJCeBnx8+umn7ccff7S5c+dakyZNrEePHjENzLdr1y5r3ry5lSlTxgUxkeZFo0SJEukSWNx6660ugGvZsqUbyVuDWerC995779nHH39sp6tChQqleWAjb7/9thUsWDBdAhtRkD127Fg7duxYunweEJU4DPkA+N7VV1/txp45cOBAovd2794d/P+oUaO86tWru3FozjrrLDdY5P79+917n332WaJxlZKaJ19++aV3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",
      "text/plain": [
       "<Figure size 640x480 with 1 Axes>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "sns.barplot(\n",
    "    data=df,\n",
    "    x=\"CaffeineConsumption\",\n",
    "    y=\"SleepDuration\"\n",
    ")\n",
    "plt.ylim(6,7.5) #same zoomed scale code\n",
    "\n",
    "plt.title(\"Caffeine Consumption vs Sleep Duration (Zoomed Scale)\")\n",
    "plt.ylabel(\"Sleep Duration (hours)\")\n",
    "plt.xlabel(\"Caffeine Consumption (mg)\")\n",
    "\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f4de6a60-d14b-4921-bfbf-4a7f5dbeda58",
   "metadata": {},
   "source": [
    "Higher caffeine consumption is generally associated with shorter sleep duration but the visual shows noticeable variability. In this visual sleep duration appears to slightly decrease with moderate caffeine intake (around 25mg), but then increases again at a higher intake (50mg). This suggests that caffeine's effect on sleep is not consistent across the Caffeine Consumption levels in this dataset. \n",
    "\n",
    "There are three things to consider with the caffeine consumption part of the dataset:\n",
    "1. Some people may have a higher tolerance to caffeine which can cause high individual variability.\n",
    "2. This column in the dataset had a large number of missing entries (256) which raises concerns about the quality of it and therefore, the reliability of it.\n",
    "3. This dataset handles smaller quantities of caffeine consumption, if you want to see the impact of caffeine on sleep specifically it would be better to use data that includes higher consumptions of caffeine such as 100mg-400mg (400mg is the safe limit for caffeine consumption so it may be difficult to find people who consume this much).\n",
    "\n",
    "These results are consistent with research from the Sleep Foundation, which reports that caffeine could interfere with sleep depending on the sensitivity of the consumer.\n",
    "(https://www.sleepfoundation.org/nutrition/caffeine-and-sleep)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "2adb5ec4-f103-40bb-a438-58255c4708d6",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/png": "iVBORw0KGgoAAAANSUhEUgAAAjcAAAHHCAYAAABDUnkqAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjgsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvwVt1zgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAOgdJREFUeJzt3QmcjeX///HPMAyyyzbImn35EkkqZYmSrahQaJSSUrZKtlC2IpQlvoyUpRKSQpStRbYU5Sf7kl0YW0Yz9//xuX7/c37nzGbOODNnzjWv5+NxmHOf+9znOvc5M+d9rutz3XeI4ziOAAAAWCJToBsAAADgT4QbAABgFcINAACwCuEGAABYhXADAACsQrgBAABWIdwAAACrEG4AAIBVCDcAAMAqhBsgBbp06SI5c+a87nr33nuvucB+s2bNkpCQEDlw4ECgm2Lt71ypUqUC3QwECcINgsL27dulbdu2UrJkScmWLZsUK1ZMmjRpIu+9916gm5ZuRUdHy4QJE6RmzZqSO3duyZs3r1SpUkW6desm//M//+Ne78cff5Q33nhDzp07l+LHmjx5svlwz8j7MRjo66wBzHXJkSOH3HLLLdKiRQuJjIyUq1evBrR9R48eNW3ctm1bQNuB4Bca6AYA16Mfvvfdd5/5I/zMM89IkSJF5PDhw7JhwwbzofPiiy+m2534zTffBOyxH3nkEVm2bJm0b9/e7Ldr166ZD+OlS5fKnXfeKRUrVnTv36FDh5pvxvrBndJwc/PNN5tt2Ca5+zGYTJkyxfQ8apj566+/ZMWKFRIRESHjx483z6tEiRIBCzf6XtQemv/85z9et02fPl1iY2MD0i4EH8IN0r233npL8uTJI5s2bYr34Xvy5ElJz7JmzRqQx9V9pR9Suu9ef/11r9vef//9G+qlyUhs3Y/aC6ph1GXw4MEyZ84c6dSpk7Rr1858cfCHf/75x/wOZMp044MEWbJk8UubkDEwLIV0b+/evWYYIKFehUKFCnld1672F154QT777DOpXLmyZM+eXerVq2eGtdQHH3wg5cqVM0NbWguTUH2E3ve2224z99UPgCeeeMJ8u70e7UovWLCg2e7FixcTrLlZs2aNaeOnn35qPjCLFy9u2tKoUSPZs2dPvG1OmjRJypQpY9py++23y/r165NVx6P7TNWvXz/ebZkzZ5YCBQqYn3UIoF+/fubn0qVLu4crXPtFhyoaNmxo9nNYWJjZp/qt35N+y/79999l7dq17vu72ucaBklOfcrmzZuladOmZp/r89X2aG9CUh566CGzfxKir3vt2rXd11euXCl33XWXeR9pr0WFChXiBZaU7sekaK/P3XffLTfddJPkypVLmjdvbvZXXNobpKEjf/785j2hbV+yZEmC+23dunXy7LPPmsfXoTINJWfPnpUb0bFjR3n66afl559/NvvK8/VNqEcusff2/PnzZeDAgWboWIe9oqKi5O+//5a+fftKtWrVzL7XNj/wwAPy66+/et2/Tp065uennnrK/V5yDXcmVHNz6dIl6dOnj+lp0venvqbvvPOOOI6T4N+FxYsXS9WqVc26+jdl+fLlN7TPkH7Rc4N0T+tsfvrpJ9mxY4f5w3Q9GgD0Q6FHjx7m+siRI82H4CuvvGKGT55//nnzQTBmzBjz4fndd9+576t/SPUPq/6R1fudOHHCDH398MMP8ssvvyQ6bKPf8PWDWT+QvvjiC/PhnJRRo0aZb7P6B//8+fOmLfrhoh8sLhoi9A+yfjD26tXLBIHWrVtLvnz5TCi63j5T+m1cP5hDQxP+VX/44Yflzz//lHnz5sm7777r/javIc3VBv0QaNmypdnGl19+afafDg+49q8OZejQoH5oDRgwwCwrXLiw+EJ74O6//37zuK+99prZz/p8Fy5cmOT9HnvsMfPBrvvf9cGoDh48aHof3n77bXNdw4S+B6pXry7Dhg0zH24aJvV19cd+TMxHH30knTt3Nu+N0aNHy+XLl80+1ZCl7yfXh7W2T7evgUCfvwYhDcD6en/++efSpk0br+3q+0L3kYbHXbt2mW3qc3YFjJR68sknZdq0aWY4VWvaUmL48OGmt0bf2zrspT//8ccfJlhor5CGVv290i8aDRo0MLeFh4dLpUqVzGujvUhaz6Tve6VDfwnRAKPvy9WrV0vXrl3NMJYOr2lY1y8j+n729P3335v3k75/NWROnDjRDDkeOnQoWSEVQcYB0rlvvvnGyZw5s7nUq1fPeeWVV5wVK1Y40dHR8dbVt3RYWJizf/9+97IPPvjALC9SpIgTFRXlXt6/f3+z3LWubq9QoUJO1apVnStXrrjXW7p0qVlv8ODB7mWdO3d2brrpJvPz999/7+TOndtp3ry5888//3i1p0GDBubisnr1arOtSpUqOVevXnUvnzBhglm+fft2c11vK1CggFOnTh3n2rVr7vVmzZpl1vPcZkJiY2PNOrpu4cKFnfbt2zuTJk1yDh48GG/dt99+22s/eLp8+XK8ZU2bNnXKlCnjtaxKlSoJtmnIkCFm23FFRkZ6PeaiRYvM9U2bNjm+OH/+vHm9+/Tp47V8zJgxTkhIiPv5vvvuu2b7p06d8mn7vuzHuM/pwoULTt68eZ1nnnnGa73jx487efLk8VreqFEjp1q1al7vH33sO++807n11lvjPcZtt93m9f7X56vLv/jiiySfj+v1SGw/nD171tzepk0b97KSJUua93tcib239b0R932jzysmJsZrme4nfe2GDRvmXqavv25Dn2dc2gZti8vixYvNum+++abXem3btjWv/Z49e9zLdL2sWbN6Lfv111/N8vfeey/BfYHgxrAU0j39Bqk9N/otTbuxtZdDvwnrt9y43fZKh3g8u6/r1q1r/tdvafqNLe7yffv2uYdFtAdBv9npsICLDiNo0ehXX30V77H0W6O2RR9TvxVqj0ByaO+QZz2O61uqZ1vOnDljClg9ewu0d0d7bq5Hv73rt9g333zTrK89M9rToj0R2tuR3FoRzx4o7WE6ffq0+bat7dTr/uLqEdP6Fi3YTS7X8Ib2cngORXzyySdyxx13mCJ0z+1rr5ovRak3sh91aEdv10Jk3W+uiw5n6XtP3ztKh2y09/DRRx+VCxcuuNfT11/fW7t37443LKo9G541KN27dzfvk6+//lpuhOvwBtqOlNKeqrg9l/p74aq7iYmJMc/NNTS4devWFD2OPlfdlz179vRarsNU+l7Q4UBPjRs3lrJly7qvay+evn9cv3OwC+EGQUGHHDQ86HDSxo0bpX///uYPsNYoaLe2J9cHmosWI6u4M0Bcy121Ctqtr/QPblwably3exZLavDRKcL64epL8XDcNroCS9y2aH2QJ/0AS+6xPvQDRYeJdu7caWah6AezfuBrW3VYIzl02EY/FHSYRAOCDhu56lT8GW40MGn41JkyOjTWqlWrZE9N1pChs+c0ALvqZLZs2WKWe66jwz5aU6JDZo8//rjZD8kJOindjxpKlNYs6X7zvOiwj6sYXofH9MN40KBB8dYbMmRIgoXzt956q9d1DQpFixa94WPsuGrFPL8E+EqHneLS/azDRNpu3Z/6Guvz++23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rzNr1ixzP32uCdHHDw0Nda5du5bg7fv37zf397x07tzZ3LZs2TKnfv36Tp48eZz8+fOb/eO5D+LeT/eV0v9feuklr8dp1aqVe7tq0qRJ7udRqFAh55FHHkn09QEQH8NSQAaVM2dOc9G6l6tXrya5rp5tuVOnTmaIpWLFitKhQwd59tlnpX///ubs6vpZ/sILL7jXX7Rokbz00kvmbM07duww6+pZ2VevXh1v23rfF198UWbPni3r16+X6tWrJ9qOoUOHyqOPPiq//fabOfGpnh1azwCv9u/fL23btpXWrVuboSZ9zAEDBiT5vHQY7t9//zXt/d884q1EiRLy+eefm5937dolx44dkwkTJpjr2rPTu3dv8/y1t0tPytqmTRv3CR03btxo/l+1apW5n559Pjl0ez179jQnftTHXL58udxzzz3Jui+A/y+BwAMgg1iwYIGTL18+J1u2bM6dd97p9O/f391z4qJ/JgYOHOi+/tNPP5llM2bMcC+bN2+e2YaLbuuZZ57x2k67du2cBx980Gu7n332mdOhQwenUqVKzpEjR7zWT6jnxrMdFy9eNMu0B0W9+uqrTtWqVb22MWDAgCR7btTrr79uem+096VZs2bOmDFjnOPHj7tvX7169XW3oU6dOmXW2759u1evzy+//OK13vV6bj7//HMnd+7cTlRUVJKPByBx9NwAGbzm5ujRo6bGpFmzZqZ4tlatWjJr1iyv9Tx7UwoXLmz+r1atmteyf/75R6Kiosz1nTt3Sv369b22odd1uadevXrJzz//LOvWrZNixYpdt72e7bjpppskd+7c7sJf7eWoU6eO1/q33377dbf51ltvyfHjx2Xq1KlSpUoV87/2Tm3fvj3J++3evVvat29vapW0HVqIrA4dOiQ3okmTJlKyZEmz3SeffFLmzJkjly9fvqFtAhkN4QbI4HSGkH6gDho0SH788Ufp0qWLDBkyxGudLFmyuH/WGUCJLXMNySSXPu5ff/1linmTw/MxXY/r62MmpECBAtKuXTt55513TAALDw83PyelRYsWZkhs+vTpJqDpRWmBdlJ0+CruENi1a9fcP+fKlUu2bt0q8+bNk6JFi8rgwYOlRo0aPs/WAjIywg0AL5UrV77hmUKVKlWKN51cr+u2PekU7Llz58rTTz8t8+fPv6HHrFChgqlXiTud3FdZs2aVsmXLuveBXlcxMTHudXQ2mfYUDRw40My20ud79uzZeNuJez/XLDCtwXHR27UuyVNoaKg0btxYxowZY+qLdAbXd9995/NzATIqpoIDGZR+QGtvRUREhBnu0R4DDQf6gdqqVasb2na/fv1M4W/NmjXNh/SXX35pCmq1uDYuLcL96KOPzBCMfqhrUXBKaAHxuHHj5NVXX5WuXbua4mfX8JqrZymupUuXmlD1+OOPS/ny5U2Pirb166+/lsjISLOODhHp/XVdLWLOnj275MuXz/T2TJs2zfSu6FDUa6+95rVtPW6OrqsFwcWLFzc9ZHny5JGGDRuaQuSvvvrKhChts2evjD7Ovn37TBGxPo62RXunNLwBSKYk6nEAWOyff/5xXnvtNadWrVpmOrNO6a5QoYIp2r18+XKiU7YTKpRNqOjW16ngn3zyiSlK1oLaxAqKPddX2u7IyMhEp4JPmTLF3O/KlSsJ7oO9e/eawmdtn04vz5s3r1OnTh2vbaphw4aZaeohISHuwt+VK1eaQmh9rOrVq5sp9XHbqFPXS5Qo4WTKlMk9FTw6Otrp3r27KWDWad4jR470Kihev369WVcLvbVNum3dNwCSL0T/SW4QAoBgosXCWiB8+PDhQDcFQBpiWAqANSZPnmxmTOmQkdb4vP32217H3wGQMRBuAFhDp2e/+eabZhaTni9LDyKoBxoEkLEwLAUAAKzCVHAAAGAVwg0AALAK4QYAAFiFcAMAAKxCuAEAAFYh3AAAAKsQbgAAgFUINwAAwCqEGwAAIDb5f7EelHVCyQOaAAAAAElFTkSuQmCC",
      "text/plain": [
       "<Figure size 640x480 with 1 Axes>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "sns.barplot(\n",
    "    data=df,\n",
    "    x=\"SmokingStatus\",\n",
    "    y=\"SleepDuration\"\n",
    ")\n",
    "plt.ylim(6.5,7.5)\n",
    "\n",
    "plt.title(\"Smoking Status vs Sleep Duration\")\n",
    "plt.ylabel(\"Sleep Duration (hours)\")\n",
    "plt.xlabel(\"Smoking Status\")\n",
    "\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8a3371e3-4a79-4748-961d-28bfb7490a63",
   "metadata": {},
   "source": [
    "Non-smokers and smokers show nearly identical average sleepdurations, with smokers sleeping only marginally less. This suggests that smoking status alone does not strongly predict sleep duration in this dataset, but still may effect other parts of sleep such as restlessness or sleep quality. ALthough the difference is very small, it aligns with other studies done by various organizations such as the one from the National Institutes of Health (https://pmc.ncbi.nlm.nih.gov/articles/PMC12357650/), making the visualization informative and relevant."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "810bf063-4e34-4200-9143-a2d083817e03",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/png": "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eOGFbrtygRQ83n///W679o8UqH7//ffu89fnru8KXdfr1q1z51LHTo1e4/bbb3eflwJAnRt9P1166aXu33rovw8FOtpP15KCQjVLPvPMM+7Hh36UefTjRd8hCsaVwK2avblz57p/JwpI1RTXrVs3F0Tq34ZH34k//fSTDRo06JTnFFESADLRf/7zH/38D3z++edu/cSJE4Fzzjkn0Lt37xT7ar+hQ4cG1zt27BjInj174Jtvvkmxr44j9957r3ve3Llzg48dOHAgULFixUCFChUCx48fd9u+/PJLt9+FF14YOHz4cHDf0aNHu+3Lly9360eOHAmUKFEiUL169cAff/wR3O/DDz90+w0ZMiS4TWU91T+h6dOnu32effbZNJ2vUaNGuf3/9a9/BbepTI0aNQoUKFAgsH//frdtw4YNbr+zzz478Ntvv6V4vQ8++MCt79mzx60/9dRTJ33d5OfeU758+cDtt98eXJ8wYYLbt1WrVsHPQFS+bNmyBf7+978Htx07dsx91s2aNQtu88qdN2/ewNatW4PbFy1a5Lbfd999wW333HNPquc3eXmvu+66QFJSUmDdunXBbb/88kvgrLPOClx22WUpyt+iRYuw8ut1c+TIEdi7d+9Jz5PeZ926dcO2LV682B1z0qRJbv3bb79161OnTg2kl64vPTd//vyB1q1bBx577LHAkiVLUuznnUe9H0/z5s0DNWrUCPz555/BbXqPjRs3Dpx33nnBbY888og7/k8//RR2zP79+7tzsHnz5nR/VpF4/+ZSW7Zt2xbcV9fIRRddFPH6u/rqq0/53vUZ67PetGlT2L6hn7H32ev53vdE4cKFA926dQt7zvbt2wOFChUK265/A3rusGHDwvatU6dO2PXwxRdfuP169eqV4r14ZdE1lidPnsCDDz4Y9rieo8/l4MGDEc4mMgNNYMj02h/9SvzLX/7i1lVL0a5dO5fQmbzqOHk18nvvved6SelXU3Jec4hqGVRLpF9sHlVP61egftn/+OOPYc9TzY5qjjz61SiqMRFVU6uG5O677w7LM1C1uGqgUmtaS42aNCQttT/e+1GNgWrKPPpVq9ot/UJWbUYonUvVOqT2flSjoPerJgWveSYa9Cs3tElKv4oVl2i7R/kW+uy8soRSrYRqKjz6DHUMvf/00nWknBkdUz2mPGrqU2K5muu8z8Gj6yO0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XdxV+3PXXXfZI4884prCli5d6mp/6tSpY5988km0ygUAABD7AEgJzqoBmjx5sguCXn/9dbddPb8UDL3zzjs2fPjwzCspAADAmQ6A8ufPbxs2bHB/b9myJUXOT7Vq1Wzu3LnRKhcAAEDsA6ARI0ZYx44drUyZMq7pS7U+AAAACZ0ErWTnq666ytavX2/nnXeeFS5cOHNLBgAAEA+9wM4++2y3AAAAJHwT2N///nfbunVrmg44ZcoUe+ONN063XAAAALGtASpevLhddNFF1qRJE7vmmmusXr16LhdIidB79uyxH3/80ebNm+d6iGn7yy+/nHklBgAAOBM1QEp4/umnn1wA9MILL1jDhg3t3HPPtRIlSljVqlVdcrRygxT4LFy40GrWrJnmAmheMU2zoWCqQYMGbnb5k9m7d6+bk6x06dKWO3duO//88133fM9DDz1k2bJlC1s0TQcAAEC6c4BKlixpAwcOdItqfTZv3mx//PGHFStWzCpXruwCjfRSc1mfPn1s7NixLvgZNWqUtWrVylavXu2Cq+SOHDliV155pXts2rRpVrZsWdu0aVOKhGzVVs2cOfN/bzJnulKdAABAgstQZFCkSBG3nK6RI0dat27d3AjTokBIE66OHz/e+vfvn2J/bf/tt99s/vz5litXLrdNtUfJKeApVarUaZcPAAAkpnRPhhotqs1ZsmSJtWjR4n+FyZ7drS9YsCDic95//31r1KiRawJTjVT16tXd6NOajT7UmjVrXC5SpUqVXPd91VadzOHDh23//v1hCwAASFwxC4B2797tAhcFMqG0vn379ojPUZ6Rmr70POX9DB482J555hl79NFHg/uoKU3TdsyYMcNefPFFN3p106ZN7cCBAycd5LFQoULBpVy5clF8pwAAIN5kqeSYEydOuPwfJVvnyJHD6tataz///LM99dRTNnToULePZqb3KBlbAVH58uXtrbfesq5du0Y87oABA1wukkc1QARBAAAkrpgFQEqeVhCzY8eOsO1aTy1/Rz2/lPuj53kuvPBCV2OkJjVNzJqcEqTVU2zt2rWplkW9ybQAAAB/SHcTmGpa1PPqdClYUQ3OrFmzwmp4tK48n0jUDV+BjPbzqHu+AqNIwY8cPHjQ1q1b5/YBAADIUAA0ffp01+29efPm9u9//9slEGeUmp3GjRtnEydOtJUrV1r37t3t0KFDwV5hGl9IzVMePa5eYL1793aBj3qMKQlaSdGevn372pw5c2zjxo2ut9j111/vaoxuvfVWPnEAAJCxAGjZsmX2zTffuLF2FIiouUqBibalV7t27ezpp5+2IUOGWO3atd2xlbzsJUar99a2bduC+ysv59NPP3WvpfyeXr16uTKEdpnXlB0KdjRA48033+zmLtPgjBrNGgAAIMM5QHXq1HGLemB98MEHNmHCBNc8pRGXlWjcqVMn15sqLXr06OGWSGbPnp1im5rHFNCkRtNxAAAAZFo3+EAgYEePHnUJyPpbgyM+//zzrqZGozwDAAAkTACkAQxVa6PE4vvuu8/VBimHR7k3GoTwsccec81TAAAACREA1ahRw02GqgEGX331VduyZYs9/vjjVqVKleA+ysHZtWtXtMsKAAAQmxwgJRZ36dLFTUR6sjF+QruqAwAAZOkASNNPAAAA+KoJ7MYbb7QnnngixfYnn3zSbrrppmiVCwAAIH4CoK+++sratGmTYrvm4NJjAAAACRcAaWqJSNNOaI4uTSIKAACQkL3AIo3xowEIq1WrFq1yAQAAxFcS9A033OAmGL3iiivcNk1g+uabb9rUqVMzo4wAAACxDYCuueYae++999wkpNOmTbO8efO6eblmzpxpzZo1i27pAAAA4mUusKuvvtotAAAAvgmARPN/7dy5M8WAh+eee240ygUAABA/AZDm+tJI0PPnzw/brslQs2XLZsePH49m+QAAAGIfAHXq1Mly5sxpH374oZsMVUEPAABAQgdAy5Ytc7PBX3DBBZlTIgAAgHgbB0hj/ezevTtzSgMAABCPAZDmAXvggQds9uzZ9uuvv7rRn0MXAACAhGsCa9Gihft/8+bNw7aTBA0AABI2APryyy8zpyQAAADxGgAx2jMAAPBdDpDMnTvXOnToYI0bN7aff/7ZbXv99ddt3rx50S4fAABA7AOgt99+21q1auXmAFu6dKkdPnzYbd+3b5+bHwwAACDhAqBHH33Uxo4da+PGjbNcuXIFtzdp0sQFRAAAAAkXAK1evdouu+yyFNsLFSpke/fujVa5AAAA4icAKlWqlK1duzbFduX/VKpUKVrlAgAAiJ8AqFu3bta7d29btGiRmwfsl19+sTfeeMP69u1r3bt3z5xSAgAAxLIbfP/+/e3EiRNuIMTff//dNYflzp3bBUA9e/aMZtkA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Wdu2ba1mzZo2adIk++WXX+y99947Q+8KAADEs5gGQEeOHLElS5a4JqpggbJnd+sLFixI9XkHDx608uXLW7ly5VyQ88MPPwQf27Bhg23fvj3smIUKFXJNayc7JgAA8I+csXzx3bt32/Hjx8NqcETrq1ativicqlWrutoh1ezs27fPnn76aWvcuLELgs455xwX/HjHSH5M77HkDh8+7BaPjiv79+9PtezHD/+RjneauE52jtKKc8m5jLfrkmsyOueRc/k/nMszcy69x9QadEqBGPr5559VwsD8+fPDtvfr1y9Qv379NB3jyJEjgcqVKwcGDRrk1r/++mt3zF9++SVsv5tuuilw8803RzzG0KFD3XNYOAdcA1wDXANcA1wDluXPwZYtW04ZP8S0BqhYsWKWI0cO27FjR9h2rSu3Jy1y5cplderUsbVr17p173k6hnqBhR6zdu3aEY8xYMAAl4jtOXHihP3222929tlnu3yjeKQoV02AW7ZscUnh4FzGA65LzmO84Zr017kMBAJ24MABK1OmzCn3jWkAlJSUZHXr1rVZs2bZddddFww+tN6jR480HUNNaMuXL7c2bdq49YoVK7ogSMfwAh59aOoN1r1794jHyJ07t1tCFS5c2LICXYTxeiFmNZxLzmW84ZrkXMajgnF+31Heb1rENAAS1bzcfvvtVq9ePatfv77rwXXo0CHXK0w6duxoZcuWtREjRrj1YcOGWcOGDa1KlSq2d+9ee+qpp1w3+DvuuMM9rhqbe++91x599FE777zzXEA0ePBgFw16QRYAAPC3mAdA7dq1s127drmBC5WkrFqbGTNmBJOYN2/e7HqGefbs2eO6zWvfIkWKuBqk+fPnuy70ngceeMAFUXfeeacLki699FJ3zOQDJgIAAH/KpkSgWBcC6adea6oVU/5S8uY7cC5jheuS8xhvuCY5l6khAAIAAL4T85GgAQAAzjQCIAAA4DsEQAAAwHcIgAAAgO8QAGVRY8aMsQoVKriu/ZrodfHixbEuUpbz1Vdf2TXXXOPGiNL4Ue+9916si5QlqTfiJZdcYmeddZaVKFHCjbe1evXqWBcrS3rxxRfdPIfeQHONGjWyTz75JNbFyvIef/zx4BhxSJ+HHnrInbvQ5YILLkiI00gAlAVNmTLFDSA5dOhQW7p0qdWqVctatWplO3fujHXRshSNFaVzp2ASGTdnzhy75557bOHChfb555/b0aNHrWXLlu78In00obNu1kuWLLH//Oc/dsUVV1jbtm3dZM/ImG+++cZeeuklF1giYy666CLbtm1bcJk3b15CnEq6wWdBqvHRL+7nn38+OH2I5mfp2bOn9e/fP9bFy5L0q+bdd99ltPAo0MCmqglSYHTZZZdF45C+VrRoUTfifdeuXWNdlCzn4MGDdvHFF9sLL7zgZgfQQLuabQBppxog1Y4vW7Ys4U4bNUBZzJEjR9yvwxYtWgS3aaRsrS9YsCCmZQNk3759wRs3Mk7zHE6ePNnVpKkpDOmnmsmrr7467PsS6bdmzRqXKlCpUiVr3769m6EhEcR8Kgykz+7du90XozdViEfrq1at4nQiplQbqTyLJk2aWPXq1fk0MkCTOyvg+fPPP61AgQKuZjJ0qh+kjYJHpQioCQyn1+Lw2muvWdWqVV3z18MPP2xNmza1FStWuLy/rIwACEBUf3HrizFRcgRiQTcaNTeoJm3atGlusmg1JxIEpd2WLVusd+/eLieNOSBPT+vWrYN/K49KAVH58uXtrbfeyvLNsgRAWUyxYsUsR44ctmPHjrDtWi9VqlTMygX06NHDPvzwQ9e7Tsm8yJikpCSrUqWK+1uTPasGY/To0S6RF2mjNAF1ClH+j0c157o2lTup+cH0PYr0K1y4sJ1//vm2du1ay+rIAcqCX476Upw1a1ZYs4PWyRNALGg+ZQU/aqr54osvrGLFinwQUaR/37phI+2aN2/umhJVk+Yt9erVc/kr+pvgJ+OUWL5u3TorXbp0lr8kqQHKgtQFXtXi+gddv35916tBiZKdO3eOddGy3D/k0F8xGzZscF+OSt4999xzY1q2rNbs9e9//9umT5/ucgK2b9/uthcqVMjy5s0b6+JlKQMGDHBNDrr+Dhw44M7r7Nmz7dNPP4110bIUXYfJc9Dy589vZ599Nrlp6dS3b183XpqavX755Rc3/IoCyFtvvdWyOgKgLKhdu3auq/GQIUPczUZdO2fMmJEiMRonp3FW/vKXv4QFlqLgUkl/SPvgfXL55ZeHbZ8wYYJ16tSJ05gOarbp2LGjSzZVAKmcCwU/V155JecRMbF161YX7Pz6669WvHhxu/TSS92YX/o7q2McIAAA4DvkAAEAAN8hAAIAAL5DAAQAAHyHAAgAAPgOARAAAPAdAiAAAOA7BEAAAMB3CICALEojBGfLls327t0bV8fTMd57772olMlvzuS5u+yyy9xI09Gwe/duK1GihBs0D8gqCICAOLZgwQI37PzVV19tiUQjmPfs2dMqVapkuXPntnLlyrnh9kPnuEtkDz30kBvBPTmNAB06+3Zmef/9990EyrfcckvUJmnWCNaaJgHIKgiAgDj26quvukBBs1hrHp5EsHHjRjehryZOfeqpp9yklZrKRdOSaF4xPytVqpQLCDPbc8895+YOzJ49ercAHe+NN96w3377LWrHBDITARAQx5O1Tpkyxbp37+5qgNIyP9nXX3/t5uTKly+fFSlSxFq1amV79uxxj2lG8V69ermmijx58rg5fb755psUx1iyZImbaFfHaNy4sa1evTrF3F+VK1e2pKQkq1q1qr3++uvpel933323a+pZvHix3XjjjXb++efbRRdd5OZi0xxDns2bN1vbtm2tQIECVrBgQbv55ptdrUXyWhS9foUKFdzcWarR0CSinmnTplmNGjXcpKyaCLNFixZu4mDRebr33nvDynbdddeFzV+m4z766KOudkPl0ISQqj3RXHxe2TRfl+aV8+hzKly4sGvKOu+889y51uewZcuW4OMPP/ywfffdd+48aPE+2+RNYAoOr7jiimD577zzTnddeFRWlfnpp592s3NrHwWRR48eTfX8q+wKPlXjFupU51vnwitv6OLRZ1imTBl79913T/r5A/GCAAiIU2+99ZZdcMEFLsjo0KGDjR8/3gKBQKr7ayb75s2bW7Vq1VzT2bx589xN7vjx4+7xBx54wN5++22bOHGiLV261KpUqeJuzMl/sQ8cONCeeeYZd1PPmTOndenSJfiYbm69e/e2+++/31asWGF33XWX++X/5Zdfpuk96bVU26ObtGbnTk6Bg5w4ccLdjLX/nDlz7PPPP7f169e7iYBDrVu3zgUMH374oVu07+OPPx5sTtIkjir/ypUrXY7TDTfccNJzGMmzzz5rTZo0sW+//dYFov/3f//nAiJ9JjqPCga1Hnrc33//3R577DGbNGmSC0qVV+U1N+k96PwpYFAZtSR/X6JATZ+PAlkFqlOnTrWZM2dajx49wvbTudd50P/12SqYOlmwrOtCwe2FF14Y3JaW860yeOVVrk/Dhg2tadOmYceuX7++zZ07N13nF4iZAIC41Lhx48CoUaPc30ePHg0UK1Ys8OWXXwYf19/6J7xnzx63fuuttwaaNGkS8VgHDx4M5MqVK/DGG28Etx05ciRQpkyZwJNPPhl2vJkzZwb3+eijj9y2P/74I1imbt26hR37pptuCrRp0ya4rv3ffffdiOVYtGiRe/ydd9456Xv/7LPPAjly5Ahs3rw5uO2HH35wz128eLFbHzp0aCBfvnyB/fv3B/fp169foEGDBu7vJUuWuP03btwY8TWaNWsW6N27d9i2tm3bBm6//fbgevny5QMdOnQIrm/bts0dc/DgwcFtCxYscNv0mEyYMMGtL1y4MLjPypUr3Ta9f6/stWrVSlGm0HP38ssvB4oUKeI+u9DPI3v27IHt27e7dZVVZTx27FjY59GuXbtUz+2zzz4bqFSpUrrPd6hevXq51925c2fY9vvuuy9w+eWXp/raQDyhBgiIQ2p2UhORajBENTH6Na6coFPVAEWiGgI1i6gmw5MrVy73i121I6HUpONRs4rs3LnT/V/7hh5DtJ78GKlJa+2LjqfEaC0e1Wyphij0tdQsc9ZZZ4WV1ytrrVq13PlQE9hNN91k48aNCzYHpkfo+ShZsqT7v46ZfJv3ut7ndckllwTXVZOXvOynon31HkJrynSuVVsT2iypmiQlykc6B5H88ccfrlkuI+dbXn75ZXcdqimwePHiYY+pqU61X0BWQAAExCHdYI4dO+ZyKnQz1aLcGzVh7du3L+JzdPOJBgVGHi/HQzfdaFBOjI65atWqqJdVdGyvrAoK1JTzySefuJv5P//5T9ecuGHDBve4EoCTB2SRcmcinY/MPEfRPAep9djKSCAoamZTUr6a9kIDQ4+a0JIHRUC8IgAC4owCH91glIejWh1vUdKsAqI333wz4vN0Q0qtG7mXtKx8lNCbvfI6FByklfJGQo8hWk/rMYoWLeryWsaMGRNMRg7ljUGk11HSsJc4LD/++KN7PD3lVTCgWhMlHSuHR+fAS9LVjVr5LB7lSimvKVqfYWhitGpsVHYv70bl8HKzUqN99ZmHniedawVuCuQyqk6dOm4YgtAgKC3ne+3atfa3v/3N/vGPf7hcqkh0/nR8ICsgAALijJJ5dXPq2rWrVa9ePWxRr6nUmsEGDBjgAhr1svr+++9dLYtqjTRInZpR1JusX79+LglZN7du3bq55gq9Tlrp+Uqw1XHXrFljI0eOtHfeecf69u2b5mMo+NHNX81vqtHScdTMoq7ZjRo1cvuot5aamdq3b+8SjdUcqETjZs2auR5qabFo0SIbPny4C0TUw0nlVA8oLwhR76qPPvrILTpXOj/RGlRStTKqKVEZ1KtOvbWUNKz37DXdqSZKga0+H/XQS07vXU1Vt99+uwssvNoXJWF7zW4ZoQBFtUChgeypzreazZRQr+eqJ5oCKG/x6FrSe23ZsmWGywacSQRAQJxRgKMbkrp1J6cASDd0BTjJqTv5Z5995moNdKNVMDF9+nTXfCbqHaXn6wZ68cUXu1/0n376qetllFbqcj169GjX7Vq5Jy+99JJNmDDBdSlPKw1+qJusxv1RbygFdldeeaWrvVJg5dXcqOwqm0Ys1vnQ8zQsQFqpK7fGT2rTpo07N4MGDXK1at5Ag+odpuDCu9Hr+CpTNKiX1YMPPmi33Xabq4FS1/LQsutzuOqqq9zrqSYqUq2ejqHPR81KyidS7Ytymp5//vnTKpuaBr0xezynOt/qDq8gUZ+RaiGVZ+QtHj3/3HPPTdEzDIhX2ZQJHetCAECiUA2ZxheKVm1SZlDNjQJYBaIa2ygaVMOlcaYU9AFZATVAAODDEadV06imwWhQM57ygrxei0BW8N+6cQCAr6g5M1qUU6SBNoGshCYwAADgOzSBAQAA3yEAAgAAvkMABAAAfIcACAAA+A4BEAAA8B0CIAAA4DsEQAAAwHcIgAAAgO8QAAEAAN/5fwRCoSluX0+LAAAAAElFTkSuQmCC",
      "text/plain": [
       "<Figure size 640x480 with 1 Axes>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "sns.barplot(\n",
    "    data=df,\n",
    "    x=\"AlcoholConsumption\",\n",
    "    y=\"SleepEfficiency\"\n",
    ")\n",
    "plt.ylim(0.5,0.8)\n",
    "\n",
    "plt.title(\"Alcohol Consumption vs Sleep Efficiency\")\n",
    "plt.ylabel(\"Sleep Efficiency (% time asleep)\")\n",
    "plt.xlabel(\"Alcohol Consumption (oz)\")\n",
    "\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "599bda9d-b0bb-423e-9d7e-dee5e0449601",
   "metadata": {},
   "source": [
    "As alcohol consumption increases, sleep efficiency tends to decrease. Even though alcohol may help you fall asleep and act as a sedative, it leads to overall less quality by disrupting sleeping patterns. Source: Sleep Foundation (https://www.sleepfoundation.org/nutrition/alcohol-and-sleep)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "463f184b-bb2d-4061-98ff-adb46df095ee",
   "metadata": {},
   "source": [
    "### Exercise Frequency vs Sleep Duration"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "6f748285-cba7-4141-bfab-6e2ce586811a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/png": "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vWfPHqtXr56NHDnS2rZt65KkAQAAMlwAtHLlStfjS9555x0rVqyYqwVSUDRmzJhTUUYAAID4BkBq/jrzzDPd3x999JG1a9fOdXuvX7++C4QAAAAyXABUoUIFmz17tuvppbyf5s2bu+V//PHHCROOAAAA0mUApLF+HnjgAStTpozL/2nQoEGwNqhWrVqnoowAACSbBuw9cOBA8BY6gC+Qom7wGvxwx44dbnBEb9Tn5cuXuxqgypUrp/ujSjd4AEj/FPSo445nzpw5lidPnriWCWnn+p2sucD+/fdfy5Url61atSpBbc+FF16YstICAACk5SawbNmy2TnnnGPHjh07dSUCAABIazlADz/8sD300EP2999/n5oSAQAAnGLJagKTF154wdavX28lS5a00qVLu3nCIscJAgAAyFABkEZ8BgAA8FUApBnfAQAAfJUDBAAA4LsaII37kylTppiP00MMAABkuABo1qxZCcYG+u6772zKlCn22GOPpWbZAAAA0kYAFDqqpue6666zatWq2YwZM6xLly6pVTYAAIC0nQOk2eAXLVqUWpsDAABI2wHQ4cOHbcyYMXbWWWelxuYAAADSVhNYgQIFwpKgNZfq/v37LXfu3Pb666+ndvkAAADiHwCNGjUqQa+wIkWKWL169VxwBAAAkOECoM6dO6fai5cpU8a2bNmSYHn37t3txRdfTLB8/PjxNnXqVFu9erW7X7t2bRs6dGjYTPS33nqr65EWqkWLFjZ//vxUKzcAAPBZACR79uyxCRMm2C+//OLuqwfY7bffbvny5UvWdlasWBE2bpACm2bNmln79u2jrr948WLr0KGDXXTRRZYzZ04bMWKENW/e3H766aew/KMrrrjCJk2aFLyfI0cOy0jU7Hjw4MHgfc3HltjYTAAA4CQDoG+++cbVqOTKlStY8/Lss8/ak08+aR999JFdcMEFSd6Wms5CDR8+3MqXL2+NGzeOuv4bb7wRdv/VV1+1d9991/U+69SpU1jAU7x4ccuoFPyEDkcwZ84cy5MnT1zLBABAhu4F1rt3b7v66qtt8+bNNnPmTHfbtGmTtW7d2u67774UF+To0aMuiVo1SUmtzTh06JAbiLFgwYIJaoqKFi1qlSpVsm7dutmuXbtSXC4AAJDxpKgGSLk4WbP+31P1d79+/axOnTopLsjs2bNd05pyeJLqwQcftJIl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Q9h9AMgwAdAnn3xiM2fOtM2bN7umsLJly9p1111nl1xyyakpIYD0IVMmC2TNHu9SAEDq9wK7++67rWnTpvbmm2/arl277M8//7Q33njDLrvsMrv33nuTsykAAIC0XwM0a9YsmzRpkk2cONHNB+YlQh8/ftwmT55s3bp1s2bNmtnVV199KssLAIAv1e47NW6vnem/o5Yv5P6lj06PW43vt093Or0BkIKfPn362K233pogCfr222+3NWvW2IQJEwiAAOAkkEsFpLEmsJUrV9o111wT83GNAP3tt9+mVrkAwNe5VN5N9wHEMQD666+/7Oyzz475uB5TXhAAAECGCYCOHj1q2bLF7taqMYC0DgAAQIbqBv/oo49a7ty5oz526NCh1CoTAABA2giANM6PEp1PtA4AAECGCYAWL158aksCAACQFgdCBAAAyAgIgAAAgO8QAAEAAN8hAAIAAL5DAAQAAHwnRQHQ7t277ZlnnrEuXbq4m/7++++/U1SAX3/91Tp27GiFChWyXLlyWfXq1e2bb76Jub7mItNErJG3atWqBdcZPHhwgscrV66covIBAICMJ9kB0GeffWZly5a1MWPGuEBIt+eff94t02PJoec2bNjQjTA9b948+/nnn23kyJFWoECBmM8ZPXq07dixI3jbtm2bFSxY0Nq3bx+2ngKi0PWWLl2a3F0FAAAZVLJGgpYePXrY9ddfb2PHjrUsWbK4ZceOHbPu3bu7x3788cckb2vEiBFWqlQpN9O8R4FUYvLly+duntmzZ7tA6rbbbkswNUfx4sWTsWcAAMAvkl0DtH79erv//vuDwY/o7z59+rjHkmPu3LlWp04dV3tTtGhRq1Wrlo0fPz5Z25gwYYI1bdrUSpcuHbZ83bp1VrJkSStXrpzdfPPNtnXr1pjbOHLkiO3bty/sBgAAMq5kB0AXXHCB/fLLLwmWa1nNmjWTta2NGze6mqSKFSvaggULrFu3btazZ0+bMmVKkp7/22+/uaazrl27hi2vV6+eTZ482ebPn++2v2nTJmvUqJHt378/6naGDRsWrFnSTbVSAAAg40p2E5gClF69ernanvr167tlX331lb344os2fPhw++GHH4Lr1qhRI9FtHT9+3NUADR061N1XDdDq1att3Lhx1rlz5xOWRYFS/vz5rW3btmHLW7ZsGVYGBUSqIXrrrbdc0nakAQMGuBosj2qACIL8IZAlm+2t0SHsPgAg40t2ANShw/+/WPTr1y/qY+pxFQgE3P/KDUpMiRIlrGrVqmHLqlSpYu++++4Jy6HXmDhxot1yyy2WPXv2RNdVkHTuuefGbKLLkSOHu8GHdL5mTfz8AQBkPMkOgNSclFrUAyxyhvm1a9cmyOeJZsmSJS6giVajE+nAgQO2YcMGFywBAAAkOwBKSnCSVL1797aLLrrINYGpZ9ny5cvtlVdecbfQ5imNFTR16tQEyc9q2jrvvPMSbPeBBx6wq666ypVVeUKDBg1yidpe7RUAAPC3FA2E+Nprr7naG/Wy2rJli1s2atQomzNnTrK2U7duXZs1a5a9+eabLpAZMmSI2456bXk0hk9kD669e/e6ZrJYtT/bt293wU6lSpVcYKVBFpWnVKRIkZTsLgAA8HsNkHpVDRw40O677z578skng3k+yrNR8NKmTZtkba9169buFot6c0VST61Dhw7FfM706dOTVQYAAOAvya4B0qjPGqvn4YcfDhsLSL25kjMIIgAAQLoJgJQEre7qkdSL6uDBg6lVLgAAgLQTAGmqilWrViVYrkEH1YUdAAAgw+UAacBAzfn1zz//uLF41HNLScwaTfnVV189NaUEAACIZwCkaSdy5cpljzzyiEtEvummm1xvMM3SfuONN6Zm2QAAANJGACTqpq6bAiANMqiJTAEAADL0OED//fefLVy40I0HpNog0YCDCoYAAAAyXA2QBj684oor3OCER44csWbNmtmZZ55pI0aMcPc1kSkAAECGqgHSTPAa82f37t3B2h+55pprbNGiRaldPgAAgPjXAH3++ef25ZdfJpiBvUyZMm7OLgAAgAxXA3T8+PHg9BeR82+pKQwAACDDBUDNmzd3c355MmXK5JKfNeP6lVdemdrlAwAAiH8T2MiRI61FixZWtWpVNxiixgFat26dFS5c2A2ICAAAkOECoLPPPtu+//57N+P6Dz/84Gp/unTp4sYFCk2KBgAAGUMgSzbbW6ND2H1fDoSYNWtW69ixY+qXBgAApD2ZMlkga3jnJ18EQHPnzk3yBq+++uqTKQ8AAEDaCIDatm2bpI0pITpaDzEAAIB0FwCp6zsAAICv5wIDAADwRQC0bNkye//998OWTZ061cqWLetmg7/zzjvdXGAAAAAZJgB6/PHH7aeffgre//HHH13396ZN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smRJoFatWooqArNmzQquN2TIkMAXX3wR2LRpU2Du3LmBYsWKuWPladasWaB79+5hr1ejRo3AwIED3d89evQInH/++e54aBsff/yx204sTzzxRKBy5cqB+fPnu/Nh0qRJgRw5cgQWL17sHt++fbvb/1GjRrn77du3D1x44YXuPJPXX389UKJECfc+bty40f1fsGBBdyxFZdA+6nh56/z222+Bl156KZAzZ0633TVr1gSWL18e9l6HHpenn346UKpUKffebd682b0/06ZNS/I5oM+K9unVV18N/O9//ws8/PDD7lyLPKdfeOGFQPPmzd3fOmb6HP3333/uftu2bQOFCxcOPPjgg8HjojLqs5iU45DUz753/i9atMi9/ssvvxxWxoMHDwYyZ84c+PTTT2O+p0gfCICQrugLKkuWLO7iFnp78skng+voy0wXoOuvvz5QtWrVwB133BF87LXXXnNfeKEXTq2fK1euwIIFC4KvoYue96Uo+hLUF7b3hZ5YgKJ19MXsXcAi6QI8dOjQsGUql768Y9H29aUbus9169aNWd6k7Kde76mnngo+rgvq2WefnawASBdCBXOhwYmUL18+eOHQurlz5w7s27cvLEitV6+e+1vLdXH0Ap5Ihw8fdgGALqKhAUdiAaPKrIA1lPY7a9asgV9//TW4bN68eQkCoEi6+NeuXTt4X+UIDci+/fbbQKZMmVygIQoEbrvttkBSaBs6Nl4g7VEw2qFDh+D9t956ywUr/fv3d++9gozQYx0ajHhBXIMGDcICIC+A8pQsWdIFIrGEHpd77703cPnll0cNOJNyDqgskUGj3v/IAEjBpYIg2b17tzvnFVTpdRXMDBs2LHjeKOA566yzknwckvrZ1/mvAFpB+/Tp06MeGy9YR/pGDhDSncsuu8zGjh0bMxdGTSOq4q9Ro4arqn/uueeCj6lafv369a4aPpSq4zds2BC8X7169bA8mlWrVlmtWrWi5txE0jpqllKzRbNmzVwThqrd1XzgleGLL74INvF4zVEqw6FDh1zTSzRq2lLVe7S8p8jynmg/9+7d65Jc69WrF9bEpmY9r6klKfQ6Bw4ccE1oodQ8EHo81fQVWhYdiz/++MP9/csvv9iRI0esSZMmUV9DzRm33HKLa67RcVQS6urVq8OORSS9vp4XSq9TqlQp10zoadCgQYLnqqlIOR4qv/ZNTZNq1vGoibBHjx42a9Ys15Q3efJkd05qH6Vbt2527bXXunI2b97crX/RRRdFLafeI73nOk9CqclJ55unffv27vXUjKRzX81qcvDgQVdONSndcccdwfVVZjU1htJ769Gx/+2332Ie80g6n1VGnYNqnlLTlPYtqeeAjv3dd98d9riO/aeffhq8v2/fPluyZIlNmDDB3VczlZoDvWZt3e68804bNGiQez2tqya9pB6HpH721az9/vvvu2bIWD3C1FSp9w3pGwEQ0h3l1ajtPzFffvllMF9CNz1H9MVZu3btYA5EKLX1h75G5Bdecijno2fPni5fQRfURx55xOWb1K9f35VBOT/t2rVL8LzIi3YoXQBi7XdkeZO6nyeifJfIgMjLh/FeR8GMLlKRdAHzRCbcKpdDuS9JPbbKL1EekfKwdGyVY6LgNpbChQu7XJzkWrZsmcvf0fujAFYXz+nTp9vIkSPD3odOnTq5cug9VDf70aNHBx9Xzynle3344YfuPVeQoYDpmWeeSfB6On7ywQcf2FlnnRX2WGiAq4vtt99+a1myZHF5TJHPHz9+fFgwK1o31jmS3PNZ+WqbNm2yefPmuUR8BaIK7BUkJPUcOBFtW3lZClI9l156qduujoWCHf24UI7P0qVLXQB0//33J/k4JPUzUb58eRfMKeBu1apV1GRxfack53OEtIkACBmOfs317t3bfRkq+FBir760dTHXF7mWKSk69Ff9iag2SQmW+uJLSi2Q6Be8bgMGDHC/dnWhVACkMqxZs+aEQdzJSMp+6qKlX7tKCvZ+Lesiq+d69CWvmqLQX+m6EIa+zs6dO13tkVcDklyqzdAFWQnNCnSiUQ2XajD0nuo4vvDCC4luU8dd5VIQ5CXI68KpJFjtj1cb99VXXyUInBVYPfzww8FlocnrHpXzvPPOc0m2Om6RwayOm8473dRbqG/fvlEDIF3wdXHfunVrsDYjGl3odf4qSLjyyivdhVlBoJKKVaO1ceNGF7gllWpB9H7pmKv2Kil0Ht1www3udt1117maIH0eknIO6NjrXFPg6Ik89uoYoKTkUDomCkS0bW+oCwVFb775pq1du9b9LUk5Dkn97Ct4njlzptu2Ar233norLAjS94tqjUJr6JBOxbsNDkgOtdFfccUVgR07doTd/vzzT/e4Eibr168fuPbaa919JXsqGdPLdVECY8WKFQOXXnqpS+hUsqSSGZXjsG3btpiJ1soVOPfcc10S9NKlS12y6jvvvBM1CVrbVK6GHlPCqPILVAYlnYqSXZWLohwWJSwrGfPNN99MNB/jREnQkeVNyn4OHz7c5VUoz+OXX35xuVKRSdDaDyUsaxtKHFUiqnIjvBwg5VNcfPHFrmzaT+WbKIFYCc7K3YhVduXoKL/Io2OhvIopU6a4JOhly5a5hNlQr7zyikto13rKC0qMzoMiRYoE3nvvvbAkaOWEKc9ESdDaJ+X2hOa6KFle743eD5Vj9OjR7hgpGTbSRRdd5Mpz9913hy1/9NFHA7Nnz3bJuXp/W7du7ZKWY9H7rvPDSwBXTtGYMWOCOSbvv/++ex0tlwEDBrhcrb///tvdV+6U8lhUViUz632aOHFiYOTIkWE5QN99913Y62r7yivS85RT5L2uJ/S4aFvKr9F5otdQjpLOCx3TpJwDyqXRa6lcer4SxkOToJV/lj9//uA+erSPygNS3p9eW1Qm3Y/MmTvRcUjuZ1/fK0pO13eJl3AuSlKPzC9D+kQAhHRFX1D6Yo68KblRHnvsMffF+NdffwWfo94guoDooud9sXXq1Mn1KFHyrb7MdPHfu3dvoj3NFMzoy1AJn0pcrVOnTuDrr79OcJHfuXOnCxRUDr2uLvT6wg/tkaQgSBdQfWFre7pA6gKfWgFQUvZTX+q9evVyr6+LT58+fdz6odvSujfccINbR72AdNGM7AWmJGZdRJRUmy1bNrfezTffHNi6dWuSAyAdG/WG0jJt45xzzkmQKK6eeDrukcm0sahn2Y033hi2TBdGXaz1viig1fsQmQStBG0FJAr0tO8qa7QAaMKECe656j0VmXir3kZ6bxU86XjqYhuLAgglKOsc1r4rcGvRooXrpfbHH3+4BPfQY6HeTArclOTvUU85Jf57AeIll1ziEnkTC4Bk3LhxwdfV+ar30RN6XHRuavtKwNa5oER+9bBM6jkg6qigc1HHVees3h/vvFi4cKEL6qLROgq2POpkoKTzyPf2RMchJZ99/YDSeaJj7fVGUy81JWMj/cukf+JdCwUgbVCyq8Z0SYtTQ2i8FuVnaGyW0Ga6WNQsozFulIycWL5QSg0ZMsTefvtt++GHH1J9236jfDk1JUaO25PWaIwiNT2q+S0yyRzpDzlAANI0JV3v2rXLJZJ7OVRJoYEi1aNI+TWpGQApmVbBmPKQnnjiiVTbrp8pnypaj7y0RvljU6dOJfjJIKgBApCma4DUC0iJuhqdWb2OlBAd72OkJFx1kVZCdmRvKwDpAwEQAADwHeYCAwAAvkMABAAAfIcACAAA+A4BEAAA8B0CIAAA4DsEQAAAwHcIgAAAgO8QAAEAAN8hAAIAAL7z/wAY4CV/m3RmiwAAAABJRU5ErkJggg==",
      "text/plain": [
       "<Figure size 640x480 with 1 Axes>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "sns.barplot(\n",
    "    data=df,\n",
    "    x=\"ExerciseFrequency\",\n",
    "    y=\"SleepDuration\"\n",
    ")\n",
    "plt.ylim(6, 8) \n",
    "\n",
    "plt.title(\"Exercise Frequency vs Sleep Duration\")\n",
    "plt.ylabel(\"Sleep Duration (hours)\")\n",
    "plt.xlabel(\"Exercise Frequency (days exercised/week)\")\n",
    "\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2863998e-b9c5-423d-95ca-3ba5e4646781",
   "metadata": {},
   "source": [
    "Participants who exercised around 4 days a week tend to get the most sleep on average, showing that regular physical activity may support better sleep quality AND duration. However sleep declines slightly for those who exercise 5 days per week showing that moderate regular exercise (3-4) is linked with optimal sleep duration."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "ce9798b6-f209-4925-a242-49b8b1017a4b",
   "metadata": {},
   "source": [
    "## Overall Insights"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "05762b72-a6b3-4128-8c28-71fafefe6025",
   "metadata": {},
   "source": [
    "The data visualizations show that different lifestyle and demographic factors influence sleep in different ways. Exercise frequency shows a moderate positive relationship with sleep duraton, with participants who exercise regularly tending to sleep slightly longer. This suggests that maintaining an active lifestyle could contribute to better sleep habits.\n",
    "\n",
    "In contrast, gender, caffeine consumption, and smoking status show only small differences in average sleep duration. Factors show high variability and overlapping patterns indicating that they are not strong independent predictors of how long individuals sleeps.\n",
    "\n",
    "Alcohol consumption stands out in having the most consistent impact on sleep quality. As alcohol inttake increases, sleep efficiency tends to decrease, suggesting that alcohol ruins normal sleep patterns and overall restfulness. Compared to other factors, alcohol shows the clearest negative association with sleep outcomes.\n",
    "\n",
    "Overall, the results suggest that behavioural choices (exercise and substance use) play a more important role in sleep health than demographic characteristics in this dataset."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c7756bd6-3337-412b-9ae5-d519ad29d218",
   "metadata": {},
   "source": [
    "## Conclusion"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7e57e0a8-9864-4a9a-beab-729b574f7db5",
   "metadata": {},
   "source": [
    "This analysis demonstrates that sleep duration and sleep quality are influenced by multiple factors rather than one variable. While regular exercise is associated with improved sleep, most demographic and habit-related factors such as gender, caffeine intake, and smoking show limited effects on sleep duration.\n",
    "\n",
    "Alcohol comsumption however, exhibits a strong and more consistent negative relationship with sleep efficiency, highlighting its disruptive role in sleep quality. These findings emphasize the importance of healthy lifestyle habits in supporting high sleep quality.\n",
    "\n",
    "In conclusion, individuals seeking to improve their sleep may benefit most from maintaining consistent physical activity and limiting alcohol intake. Although this sutdy does provide strong insights, utilizing a wide range of different datasets would be able to further enhance the understanding of how different behaviours and environmental factors impact sleep patterns."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.10"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
