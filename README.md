# Flxarjful-Ai
import React from "react"; import { Button } from "@/components/ui/button";

export default function FlxarjfulAI() { return ( <div className="min-h-screen bg-black text-white flex flex-col items-center justify-center p-8"> {/* Hero Section */} <div className="text-center space-y-4 max-w-2xl"> <h1 className="text-4xl md:text-6xl font-bold"> Unleash Your Shadow. Multiply Your Mindset. </h1> <p className="text-lg md:text-xl text-gray-300"> Meet <span className="text-white font-semibold">Flxarjful AI</span> — your personal AI built to think like you, hustle like you, and scale your vision 24/7. </p> <Button className="bg-white text-black hover:bg-gray-300 font-bold px-6 py-3 rounded-2xl shadow-xl"> Activate My Clone </Button> </div>

{/* About Section */}
  <div className="mt-24 max-w-3xl text-center space-y-6">
    <h2 className="text-3xl font-bold">What is Flxarjful AI?</h2>
    <p className="text-gray-400">
      A digital extension of your grind — trained with your voice, strategies, scripts, and playbooks.
      TikTok content? Done. Affiliate scripts? Ready. Hustle notes? Auto-dropped.
    </p>
  </div>

  {/* Features Section */}
  <div className="mt-16 grid gap-8 md:grid-cols-3 text-center">
    <div className="bg-gray-900 p-6 rounded-2xl shadow-md">
      <h3 className="text-xl font-semibold mb-2">TikTok Script Writer</h3>
      <p className="text-gray-400">Creates viral, hook-based content tailored to your brand voice.</p>
    </div>
    <div className="bg-gray-900 p-6 rounded-2xl shadow-md">
      <h3 className="text-xl font-semibold mb-2">Hustle Notes Generator</h3>
      <p className="text-gray-400">Quick mindset, productivity, and grind posts—on demand.</p>
    </div>
    <div className="bg-gray-900 p-6 rounded-2xl shadow-md">
      <h3 className="text-xl font-semibold mb-2">eBook & PDF Creator</h3>
      <p className="text-gray-400">Turn your ideas into info products while you sleep.</p>
    </div>
  </div>

  {/* CTA Section */}
  <div className="mt-24 text-center space-y-4">
    <h2 className="text-3xl font-bold">Own Your Digital Shadow.</h2>
    <p className="text-gray-400">Start building with Flxarjful AI today.</p>
    <Button className="bg-white text-black hover:bg-gray-300 font-bold px-6 py-3 rounded-2xl shadow-xl">
      Join the Hustle Circle
    </Button>
  </div>
</div>

); }

