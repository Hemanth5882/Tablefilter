# Tablefilter
live search
<!DOCTYPE HTML>
<html>
<head>
  <title>Table</title>
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://getbootstrap.com/docs/5.3/assets/css/docs.css" rel="stylesheet">

  </head>
  <style>
  .a{
padding:50px;
background-color:pink;
margin:50px;
font-style:italic;


}
  
  </style>
  <body>
<nav class="navbar navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand"></a>
    <form class="d-flex" id="searchbar">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success" type="submit">Search</button>
    </form>
  </div>
</nav>
  <div class="a mt-5">
    <div class="container">
    <table class="table table-bordered text-center" id="dataTable">
      <thead >
        <tr>
          <th>ID</th>
          <th>NAME</th>
          <th>USERNAME</th>
          <th>EMAIL</th>
		  <th>ADDRESS</th>
          <th>WEBSITE</th>
          <th>COMPANYNAME</th>
 
        </tr>
      </thead>
      <tbody>
        <tr>
          <td></td>
          <td></td>
          <td></td>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	

        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
        </tr>
        <tr>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
        </tr>
         <tr>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
          </tr>
          <tr>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
          </tr>
          <tr>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
           </tr>
          <tr>
		   <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
           </tr>
             <tr>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
        </tr>
         <tr>
		  <td></td>
          <td></td>
          <td></td>
		  <td></td>	
          <td></td>
          <td></td>
          <td></td>
        </tr>
 </tbody>
    </table>
  </div>
  </div>
  <script>
   const details1= {  "id": 1,
    "name": "Leanne Graham",
    "username": "Bret",
    "email": "Sincere@april.biz",
    "address": {
      "street": "Kulas Light",
      "suite": "Apt. 556",
      "city": "Gwenborough",
      "zipcode": "92998-3874",
      "geo": {
        "lat": "-37.3159",
        "lng": "81.1496"
      }
    },
    "phone": "1-770-736-8031 x56442",
    "website": "hildegard.org",
    "company": {
      "name": "Romaguera-Crona",
      "catchPhrase": "Multi-layered client-server neural-net",
      "bs": "harness real-time e-markets"
    }
  };
  

   const details2=   {"id": 2,
    "name": "Ervin Howell",
    "username": "Antonette",
    "email": "Shanna@melissa.tv",
    "address": {
      "street": "Victor Plains",
      "suite": "Suite 879",
      "city": "Wisokyburgh",
      "zipcode": "90566-7771",
      "geo": {
        "lat": "-43.9509",
        "lng": "-34.4618"
      }
    },
    "phone": "010-692-6593 x09125",
    "website": "anastasia.net",
    "company": {
      "name": "Deckow-Crist",
      "catchPhrase": "Proactive didactic contingency",
      "bs": "synergize scalable supply-chains"
    }
  };
 const details3=  {
    "id": 3,
    "name": "Clementine Bauch",
    "username": "Samantha",
    "email": "Nathan@yesenia.net",
    "address": {
      "street": "Douglas Extension",
      "suite": "Suite 847",
      "city": "McKenziehaven",
      "zipcode": "59590-4157",
      "geo": {
        "lat": "-68.6102",
        "lng": "-47.0653"
      }
    },
    "phone": "1-463-123-4447",
    "website": "ramiro.info",
    "company": {
      "name": "Romaguera-Jacobson",
      "catchPhrase": "Face to face bifurcated interface",
      "bs": "e-enable strategic applications"
    }
  };
  const details4= {
    "id": 4,
    "name": "Patricia Lebsack",
    "username": "Karianne",
    "email": "Julianne.OConner@kory.org",
    "address": {
      "street": "Hoeger Mall",
      "suite": "Apt. 692",
      "city": "South Elvis",
      "zipcode": "53919-4257",
      "geo": {
        "lat": "29.4572",
        "lng": "-164.2990"
      }
    },
    "phone": "493-170-9623 x156",
    "website": "kale.biz",
    "company": {
      "name": "Robel-Corkery",
      "catchPhrase": "Multi-tiered zero tolerance productivity",
      "bs": "transition cutting-edge web services"
    }
  };
  const details5= {
    "id": 5,
    "name": "Chelsey Dietrich",
    "username": "Kamren",
    "email": "Lucio_Hettinger@annie.ca",
    "address": {
      "street": "Skiles Walks",
      "suite": "Suite 351",
      "city": "Roscoeview",
      "zipcode": "33263",
      "geo": {
        "lat": "-31.8129",
        "lng": "62.5342"
      }
    },
    "phone": "(254)954-1289",
    "website": "demarco.info",
    "company": {
      "name": "Keebler LLC",
      "catchPhrase": "User-centric fault-tolerant solution",
      "bs": "revolutionize end-to-end systems"
    }
  };
  const details6= {
    "id": 6,
    "name": "Mrs. Dennis Schulist",
    "username": "Leopoldo_Corkery",
    "email": "Karley_Dach@jasper.info",
    "address": {
      "street": "Norberto Crossing",
      "suite": "Apt. 950",
      "city": "South Christy",
      "zipcode": "23505-1337",
      "geo": {
        "lat": "-71.4197",
        "lng": "71.7478"
      }
    },
    "phone": "1-477-935-8478 x6430",
    "website": "ola.org",
    "company": {
      "name": "Considine-Lockman",
      "catchPhrase": "Synchronised bottom-line interface",
      "bs": "e-enable innovative applications"
    }
  };
  const details7= {
    "id": 7,
    "name": "Kurtis Weissnat",
    "username": "Elwyn.Skiles",
    "email": "Telly.Hoeger@billy.biz",
    "address": {
      "street": "Rex Trail",
      "suite": "Suite 280",
      "city": "Howemouth",
      "zipcode": "58804-1099",
      "geo": {
        "lat": "24.8918",
        "lng": "21.8984"
      }
    },
    "phone": "210.067.6132",
    "website": "elvis.io",
    "company": {
      "name": "Johns Group",
      "catchPhrase": "Configurable multimedia task-force",
      "bs": "generate enterprise e-tailers"
    }
	};
   const details8=  {
    "id": 8,
    "name": "Nicholas Runolfsdottir V",
    "username": "Maxime_Nienow",
    "email": "Sherwood@rosamond.me",
    "address": {
      "street": "Ellsworth Summit",
      "suite": "Suite 729",
      "city": "Aliyaview",
      "zipcode": "45169",
      "geo": {
        "lat": "-14.3990",
        "lng": "-120.7677"
      }
    },
    "phone": "586.493.6943 x140",
    "website": "jacynthe.com",
    "company": {
      "name": "Abernathy Group",
      "catchPhrase": "Implemented secondary concept",
      "bs": "e-enable extensible e-tailers"
    }
  };
  const details9= {
    "id": 9,
    "name": "Glenna Reichert",
    "username": "Delphine",
    "email": "Chaim_McDermott@dana.io",
    "address": {
      "street": "Dayna Park",
      "suite": "Suite 449",
      "city": "Bartholomebury",
      "zipcode": "76495-3109",
      "geo": {
        "lat": "24.6463",
        "lng": "-168.8889"
      }
    },
    "phone": "(775)976-6794 x41206",
    "website": "conrad.com",
    "company": {
      "name": "Yost and Sons",
      "catchPhrase": "Switchable contextually-based project",
      "bs": "aggregate real-time technologies"
    }
  
  };
	console.log(details1);
	console.log(details2);
	console.log(details3);
	console.log(details4);
	

	console.log(details5);
	console.log(details6);
	console.log(details7);
	console.log(details8);
    console.log(details9);
		    function fillTableRow(rowIndex, details) {
      const table = document.getElementById("dataTable");
      const row = table.getElementsByTagName("tbody")[0].rows[rowIndex];
      row.cells[0].textContent = details.id;
      row.cells[1].textContent = details.name;
      row.cells[2].textContent = details.username;
	  row.cells[3].textContent = details.email;     
      row.cells[4].textContent = details.address.street;
      row.cells[5].textContent = details.website;
	  row.cells[6].textContent = details.company.name;
    }

					fillTableRow(0, details1);
					fillTableRow(1, details2);
					fillTableRow(2, details3);
					fillTableRow(3, details4);
					fillTableRow(4, details5);
					fillTableRow(5, details6);
				   fillTableRow(6, details7);
				   fillTableRow(7, details8);
				   fillTableRow(8, details9);

		document.querySelector("#searchbar input").addEventListener("input", function () {
  const searchTerm = this.value.toLowerCase();
  const rows = document.querySelectorAll("#dataTable tbody tr");

  rows.forEach(row => {
    const rowText = row.textContent.toLowerCase();
    if (!searchTerm || rowText.includes(searchTerm)) {
      row.style.display = "";
    } else {
      row.style.display = "none";
    }
  });
});
 
   </script>
  </body>
  </html>




  
