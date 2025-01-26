.cat_segment:before {
  animation: loop 2s cubic-bezier(0.6, 0, 0.4, 1)
                                infinite running;
  background: linear-gradient(90deg,
                        white 20%,
                      #e6e6e6 20% 80%,
                        white 80%);
  border-radius: 0.25em;
  content: "";
  display: block;
  will-change: transform;
  width: 100%
  height: 100%;
  }
