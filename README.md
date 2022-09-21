# Movie Revenue prediction
# Data Preprocessing:
-We grouped the voice actors into a list by the movie name.
-Then we fill the directors and the voice actors with an API with a TMDb library because the nulls of the directors was 428 
-and the nulls of the voice actors was 424.
-The release date column: We take only the year and convert the data type into int.
-The director column: We apply frequency encoder and apply  KNN imputer to find the rest of NULLS (19 values), now the director column has no nulls.
-The voice actor column: We apply frequency encoder and apply  KNN imputer to find the rest of NULLS (19 values), now the voice actor has no nulls.
-The MPAA-Rating column: We make one hot encoder for PG, PG-13, and other-rating. The nulls will be in other-rating column with value 0.
-The genre column: We make one hot encoder for Comedy,  Adventure, Drama and other-genre. The nulls will be in other-genre column with value 0.

