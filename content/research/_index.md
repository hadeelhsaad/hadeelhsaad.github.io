/* Full-width research text section */
.research-full {
  width: 95vw;
  max-width: 1100px;
  margin-left: 50%;
  transform: translateX(-50%);
  margin-top: 5rem;
  margin-bottom: 3rem;
}

.research-full h2 {
  font-size: clamp(2.4rem, 4vw, 4.5rem);
  line-height: 1.05;
  margin-bottom: 1.5rem;
}

.research-full p {
  font-size: 1.25rem;
  line-height: 1.7;
}

@media (max-width: 800px) {
  .research-full {
    width: 92vw;
    margin-top: 3rem;
  }

  .research-full h2 {
    font-size: 2.3rem;
  }

  .research-full p {
    font-size: 1.1rem;
  }
}
