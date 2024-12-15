# get_next_line
get_next_line project

Il y a clairement un souci de performance si ligne devient grande.
A cause des multiples mallocs et recopie de la ligne à chaque fois.
Je vais creer une version utlisant realloc pour corriger ce souci.
