printf "%o\n" $(($((5#$(echo $WATER | tr 'water' '01234') + 5#$(echo $STIR | tr 'stir.' '01234'))) | tr '01234567' 'bestchol' adds the two numbers stored in the environment variables WATER and STIR and prints the result

WATER is in base water

STIR is in base stir

The result should be in base bestchol
