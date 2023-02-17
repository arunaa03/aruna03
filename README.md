String[] deck = new String[ranks.length * suits.length];
for (int i = 0; i < ranks.length; i++)
for (int j = 0; j < suits.length; j++)
deck[suits.length*i + j] = rank[i] + " of " + suit[j];

System.out.println(rank[i] + " of " + suit[j]);
