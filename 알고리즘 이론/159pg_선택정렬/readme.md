##선택정렬

가장 작은 데이터를 선택하여 정렬을 반복한다.

N개의 입력값에서 가장작은 값을 선택 해야 하므로 N번의 비교를 한뒤 정렬

정렬된 1개를 제외한 N-1개 중 가장 작은 값을 선택 해야 하므로 N-1번의 비교를 한뒤 정렬

따라서 N + (N-1) + (N-2) + ...

(N^2 + N) / 2

따라서 시간복잡도는 O(N^2)이 됨.

