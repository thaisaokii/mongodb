# mongodb

fredinho> db.pc.insertMany ([{descricao: "Computador HP Pavilion", marca: "HP", modelo: "Pavilion", fabricacao: 2022, configuracao: { processador: "AMD Ryzen 9", memoria: "32 Gb", disco: "SSD 2Tb", monitor: "LED 24”", teclado: "ABNT2",  mouse: "Óptico 5 Botões", impressora: "Jato de Tinta Canon"},programas: ["Windows 11", "Microsoft 365", "Kaspersky Antivirus"],aquisicao: "20/06/2024",valor: 4200.00}]);
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6668716cca45a1954ecf3aab') }
}

fredinho> db.pc.insertMany ([{descricao: "Computador Dell Inspiron", marca: "Dell",modelo: "Inspiron", fabricacao: 2024, configuracao: {processador: "Intel Core i3", memoria: "8 Gb", disco: "SSD 512 Gb", monitor: "LED 20”", teclado: "ABNT2", mouse: "Óptico 3 Botões"}, programas: ["Windows 11", "Microsoft 365"], aquisicao: "10/08/2024", valor: 2700.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('666872a1ca45a1954ecf3aac') }
}

db.pc.insertMany ([{descricao: "Computador Acer Aspire", marca: "Acer", modelo: "Aspire",fabricacao: 2023, configuracao: {processador: "AMD Ryzen 7", memoria: "16 Gb", disco: "SSD 1Tb", monitor: "LED 23”", teclado: "ABNT2", mouse: "Óptico 3 Botões" }, programas: ["Windows 10", "Microsoft Office"], aquisicao: "05/09/2024", valor: 3200.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6668734bca45a1954ecf3aad') }
}
fredinho> db.pc.insertMany ([{descricao: "Computador Asus VivoPC", marca: "Asus", modelo: "VivoPC", fabricacao: 2024, configuracao: {  processador: "Intel Core i7", memoria: "12 Gb",disco: "SSD 256 Gb", monitor: "LED 22”", teclado: "ABNT2", mouse: "Óptico 3 Botões"}, programas: ["Windows 11", "Microsoft 365", "Norton Antivirus"], aquisicao: "20/10/2024", valor: 3500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('666873d9ca45a1954ecf3aae') }
}
fredinho> db.pc.insertMany ([{descricao: "Computador Lenovo IdeaCentre", marca: "Lenovo", modelo: "IdeaCentre", fabricacao: 2023, configuracao: { processador: "AMD Ryzen 5", memoria: "16 Gb",disco: "SSD 1Tb",monitor: "LED 24”",teclado: "ABNT2",mouse: "Óptico 3 Botões"},  programas: ["Windows 11", "Microsoft Office"], aquisicao: "15/11/2024", valor: 3300.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('666874b9ca45a1954ecf3aaf') }
}
fredinho> db.pc.insertMany ([{descricao: "Computador HP Slimline",marca: "HP",modelo: "Slimline",fabricacao: 2024, configuracao: {processador: "Intel Core i5", memoria: "8 Gb", disco: "SSD 512 Gb", monitor: "LED 21”", teclado: "ABNT2", mouse: "Óptico 3 Botões"}, programas: ["Windows 10", "Microsoft 365"],aquisicao: "20/12/2024",valor: 2900.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66687584ca45a1954ecf3ab0') }
}



db.pc.insertMany ([{descricao: "Computador Dell Vostro", marca: "Dell", modelo: "Vostro",fabricacao: 2024, configuracao: {processador: "Intel Core i7", memoria: "16 Gb", disco: "SSD 512 Gb", monitor: "LED 23”", teclado: "ABNT2", mouse: "Óptico 3 Botões"}, programas: ["Windows 11", "Microsoft 365", "McAfee Antivirus"], aquisicao: "25/01/2025", valor: 3600.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6668760bca45a1954ecf3ab1') }
}
fredinho> db.pc.insertMany ([{descricao: "Computador Apple iMac", marca: "Apple", modelo: "iMac", fabricacao: 2023, configuracao: { processador: "Apple M1",  memoria: "16 Gb", disco: "SSD 512 Gb",monitor: "Retina 4.5K 24”",teclado: "ABNT2",mouse: "Magic Mouse"},programas: ["macOS Monterey", "iWork"], aquisicao: "10/02/2025", valor: 4500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6668766eca45a1954ecf3ab2') }
}
fredinho> db.pc.insertMany ([{descricao: "Computador Samsung Galaxy Book", marca: "Samsung",  modelo: "Galaxy Book", fabricacao: 2024, configuracao: { processador: "Intel Core i5", memoria: "8 Gb", disco: "SSD 256 Gb", monitor: "LED 13.3”",   teclado: "ABNT2", mouse: "Touchpad" },  programas: ["Windows 11", "Microsoft 365"], aquisicao: "15/03/2025",  valor: 2800.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('666876bcca45a1954ecf3ab3') }
}
fredinho>  db.pc.insertMany ([{descricao: "Computador Lenovo Yoga", marca: "Lenovo",    modelo: "Yoga", fabricacao: 2024,  configuracao: {processador: "Intel Core i7", memoria: "16 Gb",disco: "SSD 1Tb", monitor: "IPS Touchscreen 15.6”", teclado: "ABNT2", mouse: "Touchpad" },  programas: ["Windows 11", "Microsoft Office"], aquisicao: "20/04/2025",
valor: 3700.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66687708ca45a1954ecf3ab4') }
  }
