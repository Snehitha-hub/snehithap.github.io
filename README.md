# snehithap.github.io

// src/components/Hero.jsx
import React from "react";

const Hero = () => {
  return (
    <div className="bg-white text-gray-800 py-16 px-6 text-center">
      <h1 className="text-4xl md:text-6xl font-bold">Snehitha Penumaka</h1>
      <p className="text-xl mt-4">
        MS in Business Analytics | Data Engineering Intern @ Cambard LLC
      </p>
      <p className="mt-2 text-lg">
        Turning raw data into powerful, cloud-native solutions.
      </p>
      <a
        href="/resume.pdf"
        className="mt-6 inline-block bg-blue-600 text-white px-6 py-3 rounded-xl hover:bg-blue-700"
      >
        Download Resume
      </a>
    </div>
  );
};

export default Hero;
