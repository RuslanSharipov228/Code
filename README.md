private static int[] GetColumn(int[,] c, int col_n)
        {
            int[] col = new int[c.GetLength(0)];
            for (int i = 0; i < c.GetLength(0); i++)
            {
                col[i] = c[i, col_n];
            }
            return col;
        }

        private static int[] GetRow(int[,] c, int row_n)
        {
            int[] row = new int[c.GetLength(1)];
            for (int i = 0; i < c.GetLength(1); i++)
            {
                row[i] = c[row_n, i];
            }
            return row;
        }
