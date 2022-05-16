# election

Notes:
Each election, use "HouseFirstPrefsByCandidateByVoteTypeDownload" data

Column 2 shows [DivisionID] for each seat in House of Reps. - extract this

Build a model for each division? Then run on each one using 2022 on the day?

Column 3 shows [DivisionNm] - Extract this for presenting?

Column 4 shows [CandidateID] - extract this for training

Column 8 [Elected] tells winner of seat with a Y - extract this for training

Column 17 shows [TotalVotes] - extract this for training as input against outcome of [Elected] lookup into [CandidateID]
