body {
  font-family: 'Chakra Petch', sans-serif;
  background-color: #111;
  color: #fff;
  margin: 0;
  padding: 0;
  text-align: center;
}

header {
  font-size: 2rem;
  font-weight: 700;
  padding: 1rem;
  background-color: #000;
}

/* IMAGEM DE FUNDO NA SEÇÃO CHAMADA */
.chamada {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 4rem 2rem;
  background-image: url('stock-photo-riga-latvia-bikernieki-raceway-jun-fia-idc-intercontinental-drifting-cup-kristap-2016281660.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: #fff;
  text-shadow: 0 3px 8px rgba(0, 0, 0, 0.9);
  min-height: 80vh;
  position: relative;
}

/* Sobreposição escura para destacar o texto */
.chamada::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  z-index: 0;
}

.chamada-texto {
  position: relative;
  z-index: 1;
  max-width: 800px;
}

.chamada-texto h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.categoria {
  padding: 3rem 1rem;
}

.categoria-videos {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.categoria-videos img {
  width: 300px;
  border-radius: 12px;
  transition: transform 0.3s;
}

.categoria-videos img:hover {
  transform: scale(1.05);
}
