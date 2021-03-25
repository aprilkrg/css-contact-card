https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css

<!-- HTML -->
    <div class="card">
<!--  profile  -->
        <section class="card__profile">
            <span>ONLINE</span>
            <img src="https://picsum.photos/150/150" alt="John">
            <h1>John Shoshone</h1>
        </section>
<!--  description  -->
        <section class="card__description">
<!--   stars   -->
            <ul>
            <li><i class="fas fa-star filled"></i></li>
            <li><i class="fas fa-star filled"></i></li>
            <li><i class="fas fa-star filled"></i></li>
            <li><i class="fas fa-star filled"></i></li>
            <li><i class="fas fa-star "></i></li>
            </ul>
            <p>Psychic Healer</p>
        </section>
<!--  pricing  -->
        <section class="card__pricing">
            <h3>5 mins free</h3>
            <p>then $5.99/min</p>
        </section>
<!--  contact  -->
        <section class="card__contact">
            <button>
            <i class="fas fa-phone"></i>
            </button>
            <button>
            <i class="far fa-comments"></i>
            </button>
        </section>
    </div>

<!-- BASE STYLING -->
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  height: 100vh;
  background-color: #155d5d;
  font-family: Helvetica, sans-serif;
}
<!-- POSITION THE BODY -->
body {
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #155d5d;
  font-family: Helvetica, sans-serif;
}

<!-- STYLE THE CARD -->
.card {
  background-color: #fff;
  width: 250px;
  display: flex;
  flex-direction: column;
  padding-top: 20px;
}

<!-- PROFILE SECTION -->
.card__profile {
  width: 100%;
  position: relative;
}

.card__profile span {
  font-size: 12px;
  position: absolute;
  right: 20px;
  top: -10px;
}

.card__profile img {
  margin: 0 auto;
  display: block;
  width: 100px;
  border-radius: 50%;
  border: 5px solid #72d292;
}

.card__profile h1 {
  font-size: 20px;
  text-align: center;
}

<!-- DESCRIPTION SECTION -->
.card__description ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
  margin: 0;
}

.card__description li {
  margin: 0 3px;
  color: lightgrey;
}

.card__description p {
  text-align: center;
}

.card__description .filled {
  color: goldenrod;
}

<!-- PRICING SECTION -->

.card__pricing {
  text-align: center;
}

.card__pricing h3 {
  margin: 25px 0 5px;
}

.card__pricing p {
  margin: 0 0 25px;
}

<!-- CONTACT SECTION -->

.card__contact {
    display: grid;
    grid-template-columns: 1fr 1fr;
}

.card__contact button {
  border: none;
  color: white;
  padding: 15px 0;
  font-size: 26px;
  cursor: pointer;
}

.card__contact button:first-child {
  background-color: #5bcb7e;
}
.card__contact button:nth-child(2) {
  background-color: #50b571;
}