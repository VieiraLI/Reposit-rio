# Reposit-rio
import "./index.css";

function App() {
  return (
    <>
      <h1>Bem-vindo à nossa página!</h1>
      <button className="cta-button">Clique Aqui</button>
    </>
  );
}

export default App;

body {
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 40px;
  margin: 0;
}

.cta-button {
  padding: 12px 24px;
  border: none;
  cursor: pointer;
  font-size: 16px;
  background-color: #800080;
  color: #ffffff;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #a64ca6;
}