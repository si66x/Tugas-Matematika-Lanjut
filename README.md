# Tugas-Matematika-Lanjut

# author : Muhammad Khalifah Milano
# NIM : 19523217

# soal nomor 1
?sample

# soal nomor 2
value <- sample(x = 1:100,replace = FALSE)

# soal nomor 3
G <- matrix(c(value), 10, 10, TRUE)

# soal nomor 4.1
H <- t(G)

# soal nomor 4.2
J <- H+G

# soal nomor 4.3
det(G)
det(H)
det(J)

# soal nomor 4.4
K <- cbind(G[,5],J[,5])

# soal nomor 4.5
G%*%solve(G)

# hasil dari soal nomor 4.5 adalah matrix identitas
