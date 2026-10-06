## Обо мне 🔭:
1. Меня зовут Георгий, мне 18 
2. Живу и учусь в Санкт-Петербурге
3. Учусь в ИТМО

## Мои соцсети 📫 :
|Название|Никнейм|
|---|---|
|tiktok|retor555|
|steam|2010?|
|discord|retor|

## Моя любимая цитата:
>I guess we'll never know

## Моя любимая сортировка :
'''c++
void QuickSort(int a[], int left, int right) {
  if (left >= right) {
    return;
  }
  int pivot = a[left + rand() % (right - left + 1)];
  int i = left, j = right;
  while (i <= j) {
    while (a[i] < pivot) {
      ++i;
    }
    while (a[j] > pivot) {
      --j;
    }
    if (i <= j) {
      int key = a[i];
      a[i] = a[j];
      a[j] = key;
      ++i;
      --j;
    }
  }
  QuickSort(a, left, j);
  QuickSort(a, i, right);
}
'''
## Статистика
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
<!-- Карточка с активностью -->
![GitHub Streak](https://streak-stats.demolab.com?user=retor55&theme=radical)
<!-- Карточка с языками программирования -->
![Top Langs](https://github-readme-stats-ten-gilt.vercel.app/api/top-langs/?username=retor55&layout=compact&theme=radical)
<!--
**retor55/retor55** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
