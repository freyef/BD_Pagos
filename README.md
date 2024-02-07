CREATE TABLE Pagos (
ID_Pago INT PRIMARY KEY,
ID Estudiante INT,
Fecha_Pago DATE,
Monto DECIMAL(10, 2),
Concepto VARCHAR(50),
FOREIGN KEY (ID_Estudiante) REFERENCES Estudiantes (ID_Estudiante)
);
