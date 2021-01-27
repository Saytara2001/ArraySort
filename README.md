# ArraySort




public static void sort(int... list3)
    {
        for (int i = 0; i < list3.length - 1; i++) {
            int min = list3[i];
            int minIndex = i;
            
            for (int j = i + 1; j < list3.length; j++) {
                if (list3[j] < min) {
                    min = list3[j];
                    minIndex = j;
                }
            }

            if (minIndex != i) {
                list3[minIndex] = list3[i];
                list3[i] = min;
            }
        }

    }
    This site was built using [GitHub Pages](https://www.youtube.com/watch?v=NZ4U9OZdtxk&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&index=3&ab_channel=ElzeroWebSchool).
