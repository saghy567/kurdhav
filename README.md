""import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

const Kurdhav = () => { return ( <div className="min-h-screen bg-white text-red-600"> <header className="p-4 shadow-md flex justify-between items-center bg-white"> <h1 className="text-2xl font-bold">Kurdhav</h1> <nav className="space-x-4"> <a href="#matches">Matches</a> <a href="#news">News</a> <a href="#teams">Teams</a> <a href="#about">About</a> <a href="#contact">Contact Us</a> <Button variant="outline">Sign In</Button> </nav> </header>

<main className="p-8 space-y-8">
    {/* Latest Matches */}
    <Card className="p-4">
      <CardContent>
        <h2 className="text-xl font-bold mb-2">Latest Football Matches</h2>
        <p>Scores and results from the world of football</p>
        <Button className="mt-4">View Matches</Button>
      </CardContent>
    </Card>

    {/* Upcoming Fixtures & Latest News */}
    <div className="grid grid-cols-2 gap-8">
      <Card className="p-4">
        <CardContent>
          <h2 className="text-lg font-bold mb-2">Upcoming Fixtures</h2>
          <ul className="space-y-2">
            <li>April 25 - Manchester United vs Liverpool - 17:30</li>
            <li>April 26 - Real Madrid vs Barcelona - 20:00</li>
            <li>April 27 - Inter Milan vs Juventus - 21:00</li>
          </ul>
        </CardContent>
      </Card>

      <Card className="p-4">
        <CardContent>
          <h2 className="text-lg font-bold mb-2">Latest News</h2>
          <ul className="space-y-2">
            <li>Premier League Roundup: Big Wins for Top Clubs</li>
            <li>Injury Update: Star Player Sidelined for Weeks</li>
            <li>Champions League: Key Matches to Watch</li>
          </ul>
        </CardContent>
      </Card>
    </div>

    {/* Featured Teams */}
    <Card className="p-4">
      <CardContent>
        <h2 className="text-lg font-bold mb-2">Featured Teams</h2>
        <ul className="space-y-2">
          <li>Arsenal</li>
          <li>Bayern Munich</li>
          <li>Paris Saint-Germain</li>
        </ul>
      </CardContent>
    </Card>

    {/* About Section */}
    <section id="about" className="p-4">
      <h2 className="text-xl font-bold mb-2">About Kurdhav</h2>
      <p>
        Kurdhav is your ultimate source for sports news, live match updates, 
        and exclusive insights on your favorite teams and players.
      </p>
    </section>

    {/* Contact Us Section */}
    <section id="contact" className="p-4">
      <h2 className="text-xl font-bold mb-2">Contact Us</h2>
      <p>Email: info@kurdhav.com</p>
      <p>Phone: +964 750 123 4567</p>
    </section>

    {/* Sign In Form */}
    <section id="signin" className="p-4">
      <h2 className="text-xl font-bold mb-2">Sign In</h2>
      <form className="space-y-4">
        <input type="email" placeholder="Email" className="w-full p-2 border" />
        <input type="password" placeholder="Password" className="w-full p-2 border" />
        <Button className="w-full">Sign In</Button>
      </form>
    </section>
  </main>
</div>

); };

export default Kurdhav; ""

