# susun-kursi
//function managePerson(arr, rowSeats) {

  INISIALISASI seats = []
  LOOPING DARI i=0 SAMPAI i<row
    seats.push([])

  // CONSOLE.LOG(seats) ==> [[],[],[]]

	INISIALISASI row = 0

	LOOPING DARI i=0 SAMPAI i<arr.length
		seats[row].push(arr[i])
		IF row < 2
			row++
		ELSE
			row = 0

	LOOPING DARI i=0 SAMPAI i<seats.length
		CETAK `Baris ${i+1} : `, seats[i]
