## Componente Square:
El componente Square representa un cuadrado en el tablero del juego. Aquí hay un ejemplo de cómo se utiliza:

function Square({ value, onSquareClick }) {
  return (
    <button className="square" onClick={onSquareClick}>
      {value}
    </button>
  );
}

## Componente Board:

El componente Board representa el tablero completo del juego. Aquí hay un ejemplo:

function Board({ squares, onPlay }) {
  return (
    <div className="board">
      {squares.map((value, index) => (
        <Square key={index} value={value} onSquareClick={() => onPlay(index)} />
      ))}
    </div>
  );
}

## Componente Game:

El componente Game es el componente principal que representa el juego. Aquí está un ejemplo:

export default function Game() {
  return (
    <div className="game">
      <div className="game-board">
        <Board squares={currentSquares} onPlay={handlePlay} />
      </div>
      <div className="game-info">
        <ol>{moves}</ol>
      </div>
    </div>
  );
}
Este componente renderiza el tablero y la información del juego.


## Función calculateWinner:

La función calculateWinner determina si hay un ganador en el juego. Aquí hay un ejemplo:

function calculateWinner(squares) {
  const lines = [
    [0, 1, 2],
    [3, 4, 5],
    [6, 7, 8],
    // Otras combinaciones posibles...
  ];

  for (let i = 0; i < lines.length; i++) {
    const [a, b, c] = lines[i];
    if (squares[a] && squares[a] === squares[b] && squares[a] === squares[c]) {
      return squares[a];
    }
  }
  return null;
}


### Ejemplo de uso en el componente Board para determinar el estado del juego:

const winner = calculateWinner(squares);


# En resumen, el proyecto utiliza componentes de React para representar el juego de tres en línea. El componente Game es el componente principal que maneja el estado del juego y renderiza el tablero y la información del juego. Los componentes Square y Board son componentes reutilizables que representan los elementos individuales del juego y el tablero, respectivamente. La función calculateWinner se utiliza para determinar si hay un ganador en el juego.
