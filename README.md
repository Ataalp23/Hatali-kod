# Hatali-kod
hatali
ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin-bottom: 10px;
  padding: 10px;
  border-radius: 5px;
  color: #fff;
  font-size: 18px;
  font-family: Arial, sans-serif;
  transition: all 0.3s ease;
}

/* Renkler */
li:nth-child(odd) {
  background-color: #ff0000; /* Kırmızı */
}

li:nth-child(even) {
  background-color: #0000ff; /* Mavi */
}

/* Geçiş efektleri */
li:hover {
  transform: scale(1.05);
  background-color: #800080; /* Mor */
}
